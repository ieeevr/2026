---
layout: ieeevr-default
title: "Papers"
subtitle: "IEEE VR 2026"
title_separator: "|"
---
<style>
html { scroll-behavior: smooth; }

h3 {
    margin-top: 1.5rem;
    margin-bottom: 0.8rem;
    font-size: 1em;
    border-bottom: 2px solid #262188;
    padding-bottom: 5px;
    padding-bottom: 1rem;
}

.table-scroll {
    width: 100%;
    overflow-x: auto;
    margin-bottom: 40px;
    -webkit-overflow-scrolling: touch;
    border-radius: 20px;
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.08);
}
    
table {
    border-collapse: collapse;
    width: 100%;
    min-width: 600px;
    table-layout: fixed;
    margin-bottom: 0;
}

thead {
    background-color: #262188 !important;
    color: #fff;
    border-bottom: none;
}   

th { font-size: 1.1rem; }

td {
    font-size: 0.8rem;
    border-bottom: 1px solid #eee !important;
    padding: 10px 25px 5px;
    text-align: center;
    word-wrap: break-word;
    vertical-align: middle;
}   

.time-col {
    background-color: #F2F2F2;
    font-weight: bold;
    color: #333;
    font-size: 0.7rem;
    line-height: 1.4;
}

.type-Parallel {
    background-color: #f2fbff;
    transition: background 0.2s;
    text-align: left;
}

.type-Parallel:hover {
    background-color: #9dcde4;
}

.session-link {
    text-decoration: none;
    color: #2c7fa8;
    display: block;
    width: 100%;
    height: 100%;
    padding: 5px 0;
}

.session-link:hover { text-decoration: none; }
.session-link:hover .s-title { text-decoration: underline; }

.s-title {
    display: block;
    font-weight: bold;
    font-size: 1.05em;
    margin-bottom: 3px;
}

.s-venue {
    display: block;
    font-size: 0.85em;
    color: #555;
    font-weight: normal;
}

#session-details { margin-top: 50px; }
.session-container { margin-bottom: 25px; padding-top: 20px; }
.session-title-wrapper { margin: 5px 0; }

.session-id-tag {
    font-size: 1.4rem;
    color: #262188;
    font-weight: bold;
}

.session-name-title {
    font-size: 1.4rem;
    font-weight: bold;
    color: #262188;
}

.session-chair-text {
    font-size: 0.8rem;
    color: #444;
}
.session-chair-text.last { margin-bottom: 15px; }

.paper-block {
    padding: 12px 0;
    font-size: 0.8rem;
    line-height: 1.6;
}

.paper-item {
    padding-left: 14px;  
    text-indent: -14px;  
    margin-bottom: 4px;
}

.paper-id-text { display: none; }
.paper-title-text { font-weight: bold; color: #000; }

.toggle-btn {
    cursor: pointer;
    color: #262188;
    font-weight: bold;
    user-select: none;
    display: inline-block;
    margin-top: 5px;
    text-indent: 0;
}
.toggle-btn:hover { text-decoration: underline; }

.toggle-content {
    display: none;
    margin-top: 5px;
    padding-left: 10px;
    border-left: 2px solid #ddd;
    color: #444;
    text-indent: 0;
    line-height: 1.5;
}
.toggle-content.show { display: block; }

.div-light { border: 0; border-top: 1px solid #eee; margin: 10px 0; }
.div-heavy { border: 0; border-top: 3px solid #262188; margin: 5px 0; }

/* 로딩 애니메이션 디자인 */
#loading-message {
    text-align: center;
    font-size: 1.2rem;
    color: #262188;
    margin: 50px 0;
    font-weight: bold;
}
</style>

<script src="https://cdnjs.cloudflare.com/ajax/libs/PapaParse/5.4.1/papaparse.min.js"></script>

<p class="big_title">Papers</p>
<div id="loading-message">Loading schedule data...</div>
<div id="schedule-tables"></div>
<div id="session-details"></div>

<script>
document.addEventListener("DOMContentLoaded", function() {
    // 1. CSV 파일 가져오기 (파일 이름이 papers.csv 인 경우)
    // github 경로에 맞게 파일명을 수정하셔도 됩니다.
    const csvFileName = "papers.csv"; 

    Papa.parse(csvFileName, {
        download: true,
        header: true,
        skipEmptyLines: true,
        complete: function(results) {
            document.getElementById("loading-message").style.display = "none";
            processData(results.data);
        },
        error: function(err) {
            document.getElementById("loading-message").innerText = "Error loading data. Please check the CSV file.";
            console.error("CSV Parse Error:", err);
        }
    });

    function processData(data) {
        let scheduleMap = new Map(); // 날짜와 시간 보관
        let psData = {}; // 세션 및 논문 데이터 보관

        let curDate = "", curTime = "", curPs = "";
        let curSess = null;

        // 2. CSV 데이터를 순회하며 구조화
        data.forEach(row => {
            // 제목이 비어있으면 건너뛰기
            if (!row['Paper Title'] || row['Paper Title'].trim() === "") return;

            // [Parallel Session] 파싱 (형식: "1\n\nMonday 23 March\n1130-1230")
            let psRaw = row['Parallel Session'];
            if (psRaw && psRaw.trim() !== "") {
                let parts = psRaw.split('\n').map(s => s.trim()).filter(s => s !== '');
                if (parts.length >= 3) {
                    curPs = parts[0];
                    curDate = parts[1];
                    curTime = parts[2];

                    if (!scheduleMap.has(curDate)) scheduleMap.set(curDate, new Map());
                    if (!scheduleMap.get(curDate).has(curTime)) scheduleMap.get(curDate).set(curTime, curPs);
                }
            }

            // [Session ID] 가 있으면 새로운 세션 시작
            let sessIdRaw = row['Session ID'];
            if (sessIdRaw && sessIdRaw.trim() !== "") {
                if (!psData[curPs]) psData[curPs] = [];
                curSess = {
                    id: sessIdRaw.trim(),
                    name: row['Session Name'] ? row['Session Name'].trim() : "TBA",
                    venue: row['Venue'] ? row['Venue'].trim() : "TBA", // Venue(장소) 추가!
                    chair: row['Session Chair'] ? row['Session Chair'].trim() : "TBA",
                    papers: []
                };
                psData[curPs].push(curSess);
            }

            // [Paper] 추가 (이전 세션에 계속 누적)
            if (curSess) {
                curSess.papers.push({
                    id: row['Paper ID'] ? row['Paper ID'].trim() : "N/A",
                    title: row['Paper Title'].trim(),
                    authors: row['Author List'] ? row['Author List'].trim() : "N/A",
                    abstract: row['Abstract'] ? row['Abstract'].trim() : "Abstract not available."
                });
            }
        });

        // 3. scheduleMap을 배열 형태로 변환 (렌더링을 위해)
        let scheduleMeta = [];
        for (let [day, timeMap] of scheduleMap.entries()) {
            let times = [];
            for (let [time, ps] of timeMap.entries()) {
                times.push({ time: time, ps: ps });
            }
            scheduleMeta.push({ day: day, times: times });
        }

        // 4. 화면에 그리기 호출
        renderHTML(scheduleMeta, psData);
    }

    function renderHTML(scheduleMeta, psData) {
        const tableContainer = document.getElementById("schedule-tables");
        const detailsContainer = document.getElementById("session-details");

        let tablesHTML = "";
        let detailsHTML = "";

        scheduleMeta.forEach(dayInfo => {
            tablesHTML += `<div class="table-scroll"><table>`;
            tablesHTML += `<colgroup><col style="width: 25%;"><col style="width: 75%;"></colgroup>`;
            tablesHTML += `<thead><tr><th colspan="2" style="text-align: left; padding-left: 20px;">${dayInfo.day}</th></tr></thead><tbody>`;

            dayInfo.times.forEach(slot => {
                const sessions = psData[slot.ps];
                
                if (sessions && sessions.length > 0) {
                    sessions.forEach((sess, index) => {
                        tablesHTML += `<tr>`;
                        
                        if (index === 0) {
                            tablesHTML += `<td rowspan="${sessions.length}" class="time-col">${slot.time}</td>`;
                        }
                        
                        // 표 안에 Venue(장소)가 노출되도록 반영
                        tablesHTML += `
                            <td class="type-Parallel">
                                <a href="#session-${sess.id}" class="session-link">
                                    <span class="s-title">ID ${sess.id}: ${sess.name}</span>
                                    <span class="s-venue">📍 ${sess.venue}</span>
                                </a>
                            </td>
                        `;
                        tablesHTML += `</tr>`;

                        const fullDateTime = `${dayInfo.day} ${slot.time}`;

                        // 세션 디테일(아래쪽 정보) 영역
                        detailsHTML += `
                            <div id="session-${sess.id}" class="session-container">
                                <div class="session-title-wrapper">
                                    <span class="session-id-tag">Session ID ${sess.id} : </span>
                                    <span class="session-name-title">${sess.name}</span>
                                </div>
                                <div class="session-chair-text">- Date & Time: ${fullDateTime}</div>
                                <div class="session-chair-text">- Room(Venue): ${sess.venue}</div>
                                <div class="session-chair-text last">- Session Chair: ${sess.chair || "TBA"}</div>
                                <hr class="div-light">
                        `;

                        // 논문 목록 렌더링
                        sess.papers.forEach((paper, pIdx) => {
                            detailsHTML += `
                                <div class="paper-block paper-item">
                                    <span class="paper-id-text">· Paper ID: ${paper.id}<br></span>
                                    <span class="paper-title-text">${paper.title}</span><br>
                                    
                                    <div>
                                        <span class="toggle-btn" onclick="this.nextElementSibling.classList.toggle('show')">· Author List ▼</span>
                                        <div class="toggle-content">${paper.authors}</div>
                                    </div>
                                    
                                    <div>
                                        <span class="toggle-btn" onclick="this.nextElementSibling.classList.toggle('show')">· Abstract ▼</span>
                                        <div class="toggle-content">${paper.abstract}</div>
                                    </div>
                                </div>
                            `;
                            if (pIdx < sess.papers.length - 1) {
                                detailsHTML += `<hr class="div-light">`;
                            }
                        });

                        detailsHTML += `</div>`;
                        
                        if (index < sessions.length - 1) {
                            detailsHTML += `<hr class="div-heavy">`;
                        }
                    });
                    
                    detailsHTML += `<hr class="div-heavy">`;
                }
            });
            tablesHTML += `</tbody></table></div>`;
        });

        tableContainer.innerHTML = tablesHTML;
        detailsContainer.innerHTML = detailsHTML;
    }
});
</script>
