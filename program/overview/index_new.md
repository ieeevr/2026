---
layout: ieeevr-default
title: "Program Overview"
subtitle: "IEEE VR 2026"
title_separator: "|"
---

<style>
/* 1. 폰트 크기 반응형 적용 (최소 9px ~ 최대 11px) */

h3 {
	margin-top: 1rem;
	margin-bottom: 0.5rem;
    font-size: 1em;
    border-bottom: 1px solid #066569;
}
/* 2. 가로 스크롤을 위한 래퍼(Wrapper) 스타일 정의 */
.table-scroll {
	width: 100%;
	overflow-x: auto;       /* 내용이 넘치면 스크롤 생성 */
	margin-bottom: 40px;    /* 표 아래 여백 */
	-webkit-overflow-scrolling: touch; /* 모바일 부드러운 스크롤 */
    /* 요청하신 CSS 추가 */
    border-radius: 20px;
    box-shadow: 0 12px 30px rgba(0, 0, 0, 0.08);
}
table {
	border-collapse: collapse;
	width: 100%;
	/* 3. 모바일에서 표가 찌그러지지 않도록 최소 너비 설정 */
	min-width: 600px;
	table-layout: fixed;
	margin-bottom: 0; /* 마진은 .table-scroll에서 제어 */
}
th, td {
	border: 1px solid #888;
	padding: 4px;
	text-align: center;
	word-wrap: break-word;
	vertical-align: middle;
	font-size:0.7rem
}
/* 헤더 스타일 */
.day-header {
	background-color: #4472C4;
	color: white;
	font-size: 1.2em;
	font-weight: bold;
	padding: 8px;
}
.sub-header {
	background-color: #D9E1F2;
	font-weight: bold;
	height: 30px;
	font-size: 0.6rem
}
/* 컬럼 스타일 */
.time-col {
	background-color: #262188; /* 변경됨 */
	font-weight: bold;
	color: #fff; /* 변경됨 */
	font-size:0.5rem;
	vertical-align: top
}
.reg-col {
	background-color: #D3D6EE; /* 푸른 파스텔톤으로 변경 */
	font-weight: bold;
	color: #222;
}
/* 세션 타입별 컬러 (전체적으로 #262188 기준 푸른 계열 파스텔톤 적용) */
.type-break {
	background-color: #F0F2F8;
	color: #000;
} /* 휴식 */
.type-lunch {
	background-color: #F0F2F8;
	color: #000;
} /* 점심 */
.type-keynote {
	background-color: #C5CAE9;
	color: #1A1668;
	font-weight: bold;
} /* 키노트/오프닝 */
.type-social {
	background-color: #D0D4F0;
	color: #1A1668;
	font-weight: bold;
} /* 리셉션/디너 */
.type-workshop {
	background-color: #DCE1F6;
	color: #000;
} /* 워크숍/세션 */
.type-empty {
	background-color: #FFFFFF;
}
.type-tuto {
	background-color: #E8EAF6;
	color: #000;
}
.type-doct {
	background-color: #E0E4F8;
	color: #000;
}
.type-Future {
	background-color: #D4DAF5;
	color: #000;
}
.type-Research {
	background-color: #C8CEEE;
	color: #000;
}
.type-Welcome {
	background-color: #B8C0E8;
	color: #000;
}

.type-Parallel {
	background-color: #E4E7F9;
	color: #000;
}

/* 링크 컬러 변경 (#e70087 -> #262188) */
.type-Parallel a {
    color: #262188;
    text-decoration: underline;
    font-weight: bold;
    transition: color 0.2s;
}

.type-Parallel a:hover {
    color: #066569;
}
</style>
<p class="big_title">Program Overview</p>
<h3>Day 1: Saturday, March 21</h3>
<div class="table-scroll">
  <table>
    <colgroup>
    <col style="width: 5%;">
    <col style="width: 5%;">
    <col style="width: 30%;">
    <col style="width: 30%;">
    <col style="width: 30%;">
    </colgroup>
    <thead>
    </thead>
    <tbody>
      <tr>
        <td class="time-col">08:00</td>
        <td rowspan="40" class="reg-col">R<br>
        e<br>
        g<br>
        i<br>
        s<br>
        t<br>
        r<br>
        a<br>
        t<br>
        i<br>
        o<br>
        n</td>
        <td colspan="3" ></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td rowspan="9" class="type-workshop"><a href="https://ieeevr.org/2026/program/workshop/">Workshops</a><br>
          (08:30-12:30)</td>
        <td rowspan="3" class="type-tuto"><a href="https://ieeevr.org/2026/program/tutorials/">Tutorials</a><br>
          (08:30-10:00)</td>
        <td rowspan="3" class="type-doct">Doctoral Consortium</td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" class="type-break">Break (Catered)</td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
        <td rowspan="4" class="type-tuto"><a href="https://ieeevr.org/2026/program/tutorials/">Tutorials</a><br>
          (10:30-12:00)</td>
        <td rowspan="4" class="type-doct">Doctoral Consortium</td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td colspan="2" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
        <td colspan="3" rowspan="2" class="type-lunch">Lunch (Not Catered)</td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td rowspan="8" class="type-workshop"><a href="https://ieeevr.org/2026/program/workshop/">Workshops</a><br>
          (14:00-18:00)</td>
        <td rowspan="3" class="type-tuto"><a href="https://ieeevr.org/2026/program/tutorials/">Tutorials</a><br>
          (14:00-15:30)</td>
        <td rowspan="3" class="type-doct">Doctoral Consortium</td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
        <td colspan="2" class="type-break">Break (Catered)</td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td rowspan="3" class="type-tuto"><a href="https://ieeevr.org/2026/program/tutorials/">Tutorials</a><br>
          (16:00-17:30)</td>
        <td rowspan="3" class="type-doct">Doctoral Consortium</td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
        <td class="time-col">17:30</td>
        <td colspan="2" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col">18:00</td>
        <td colspan="3" class="type-empty"></td>
      </tr>
    </tbody>
  </table>
</div>
<h3>Day 2: Sunday, March 22</h3>
<div class="table-scroll">
  <table>
  <tbody>
    </tbody>
  <colgroup>
  <col style="width: 5%;">
  <col style="width: 5%;">
  <col style="width: 30%;">
  <col style="width: 30%;">
  <col style="width: 30%;">
  </colgroup>
  <thead>
  </thead>
  <tbody>
    <tr>
      <td class="time-col">08:00</td>
      <td rowspan="39" class="reg-col">R<br>
        e<br>
        g<br>
        i<br>
        s<br>
        t<br>
        r<br>
        a<br>
        t<br>
        i<br>
        o<br>
        n</td>
      <td colspan="3" ></td>
    </tr>
    <tr>
      <td class="time-col">08:30</td>
      <td rowspan="8" class="type-workshop"><a href="https://ieeevr.org/2026/program/workshop/">Workshops</a><br>
        (08:30-12:30)</td>
      <td rowspan="3" class="type-tuto"><a href="https://ieeevr.org/2026/program/tutorials/">Tutorials</a><br>
        (08:30-10:00)</td>
      <td rowspan="3" class="type-Future">Future Faculty Forum</td>
    </tr>
    <tr>
      <td class="time-col">09:00</td>
      </tr>
    <tr>
      <td class="time-col">09:30</td>
      </tr>
    <tr>
      <td class="time-col">10:00</td>
      <td colspan="2" class="type-break">Break (Catered)</td>
    </tr>
    <tr>
      <td class="time-col">10:30</td>
      <td rowspan="3" class="type-tuto"><a href="https://ieeevr.org/2026/program/tutorials/">Tutorials</a><br>
        (10:30-12:00)</td>
      <td rowspan="3" class="type-Future">Future Faculty Forum</td>
    </tr>
    <tr>
      <td class="time-col">11:00</td>
      </tr>
    <tr>
      <td class="time-col">11:30</td>
      </tr>
    <tr>
      <td class="time-col">12:00</td>
      <td colspan="2" class="type-empty"></td>
    </tr>
    <tr>
      <td class="time-col">12:30</td>
      <td rowspan="3"></td>
      <td colspan="2" rowspan="3" class="type-lunch">Lunch (Not Catered)</td>
    </tr>
    <tr>
      <td class="time-col">13:00</td>
      </tr>
    <tr>
      <td class="time-col">13:30</td>
      </tr>
    <tr>
      <td class="time-col">14:00</td>
      <td rowspan="8" class="type-workshop"><a href="https://ieeevr.org/2026/program/workshop/">Workshops</a><br>
        (14:00-18:00)</td>
      <td rowspan="3" class="type-tuto"><a href="https://ieeevr.org/2026/program/tutorials/">Tutorials</a><br>
        (14:00-15:30)</td>
      <td rowspan="3" class="type-Future">Future Faculty Forum</td>
    </tr>
    <tr>
      <td class="time-col">14:30</td>
      </tr>
    <tr>
      <td class="time-col">15:00</td>
      </tr>
    <tr>
      <td class="time-col">15:30</td>
      <td colspan="2" class="type-break">Break (Catered)</td>
    </tr>
    <tr>
      <td class="time-col">16:00</td>
      <td rowspan="3" class="type-tuto"><a href="https://ieeevr.org/2026/program/tutorials/">Tutorials</a><br>
        (16:00-17:30)</td>
      <td rowspan="3" class="type-Future">Future Faculty Forum</td>
    </tr>
    <tr>
      <td class="time-col">16:30</td>
      </tr>
    <tr>
      <td class="time-col">17:00</td>
      </tr>
    <tr>
      <td class="time-col">17:30</td>
      <td colspan="3" rowspan="2" >&nbsp;</td>
    </tr>
    <tr>
      <td class="time-col">18:00</td>
      <td >&nbsp;</td>
    </tr>
  </tbody>
  <tbody>
  </tbody>
  </table>
</div>
<h3>Day 3: Monday, March 23</h3>
<div class="table-scroll">
  <table>
    <colgroup>
    <col style="width: 5%">
    <col style="width: 5%">
    <col style="width: 45%">
    <col style="width: 45%">
    </colgroup>
    <thead>
    </thead>
    <tbody>
      <tr>
        <td class="time-col">08:00</td>
        <td rowspan="37" class="reg-col">R<br>
        e<br>
        g<br>
        i<br>
        s<br>
        t<br>
        r<br>
        a<br>
        t<br>
        i<br>
        o<br>
        n</td>
        <td colspan="2" ></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td rowspan="2" class="type-keynote">Opening & Awards<br>
          (08:30-09:30)</td>
        <td rowspan="5" ></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td class="type-break">Break</td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td rowspan="2" class="type-keynote"><a href="/2026/program/keynote-speakers/#link01">Keynote 1</a><br>
        (10:00-11:00)</td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
        <td class="type-break">Break</td>
        <td class="type-Research">Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
        <td rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-1" target="_blank">Parallel Sessions 1</a><br>
          (11:30-12:30)</td>
        <td rowspan="3" ></td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td rowspan="3" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
        <td rowspan="2" class="type-Research">Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-5" target="_blank">Parallel Sessions 2</a><br>
          (14:00-15:00)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-9" target="_blank">Parallel Sessions 3</a><br>
          (15:00-16:00)</td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td class="type-break">Break</td>
        <td class="type-Research">Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-13" target="_blank">Parallel Sessions 4</a><br>
          (16:30-17:30)</td>
        <td rowspan="2" ></td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
         <td class="time-col">17:30</td>
        <td colspan="2" rowspan="5" class="type-Welcome">Welcome Reception<br>
          (17:30-19:30)</td>
      </tr>
      <tr>
        <td class="time-col">18:00</td>
      </tr>
      <tr>
         <td class="time-col">18:30</td>
      </tr>
      <tr>
         <td class="time-col">19:00</td>
      </tr>
      <tr>
        <td class="time-col">19:30</td>
      </tr>
    </tbody>
  </table>
</div>
<h3>Day 4: Tuesday, March 24</h3>
<div class="table-scroll">
  <table>
    <colgroup>
    <col style="width: 5%">
    <col style="width: 5%">
    <col style="width: 23%">
    <col style="width: 22%">
    <col style="width: 45%">
    </colgroup>
    <thead>
    </thead>
    <tbody>
      <tr>
        <td class="time-col">08:00</td>
        <td rowspan="41" class="reg-col">R<br>
        e<br>
        g<br>
        i<br>
        s<br>
        t<br>
        r<br>
        a<br>
        t<br>
        i<br>
        o<br>
        n</td>
        <td colspan="3" ></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td colspan="2" rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-17" target="_blank">Parallel Sessions 5</a><br>(08:30-09:30)</td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td colspan="2" class="type-break">Break</td>
        <td class="type-Research">Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" rowspan="2" class="type-keynote"><a href="/2026/program/keynote-speakers/#link02">Keynote 2</a><br>
        (10:00-11:00)</td>
        <td rowspan="6"></td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
        <td colspan="2" class="type-break">Break </td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
        <td colspan="2" rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-21" target="_blank">Parallel Sessions 6</a><br>
          (11:30-12:30)</td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td colspan="2" rowspan="3" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
        <td rowspan="2" class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td colspan="2" rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-25" target="_blank">Parallel Sessions 7</a><br>
          (14:00-15:00)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-29" target="_blank">Parallel Sessions 8</a><br>
          (15:00-16:00)</td>
        <td rowspan="3" class="type-workshop"><a href="https://ieeevr.org/2026/program/panels/">Panel Session</a><br>
          (15:00-16:30)</td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td class="type-break">Break</td>
        <td class="type-Research">Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td colspan="2" rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-33" target="_blank">Parallel Sessions 9</a><br>
          (16:30-17:30)</td>
        <td rowspan="2" ></td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
         <td class="time-col">17:30</td>
        <td colspan="3" rowspan="2" ></td>
      </tr>
      <tr>
         <td rowspan="2" class="time-col">18:00</td>
      </tr>
      <tr>
        <td colspan="3" rowspan="7" class="type-Welcome">Gala Dinner<br>
          (18:00-21:00)</td>
      </tr>
      <tr>
         <td class="time-col">18:30</td>
      </tr>
      <tr>
         <td class="time-col">19:00</td>
      </tr>
      <tr>
         <td class="time-col">19:30</td>
      </tr>
      <tr>
         <td class="time-col">20:00</td>
      </tr>
      <tr>
         <td class="time-col">20:30</td>
      </tr>
      <tr>
        <td class="time-col">21:00</td>
      </tr>
    </tbody>
  </table>
</div>
<h3>Day 5: Wednesday, March 25</h3>
<div class="table-scroll">
  <table>
    <colgroup>
    <col style="width: 5%">
    <col style="width: 5%">
    <col style="width: 23%">
    <col style="width: 22%">
    <col style="width: 45%">
    </colgroup>
    <thead>
    </thead>
    <tbody>
      <tr>
        <td class="time-col">08:00</td>
        <td rowspan="33" class="reg-col">R<br>
        e<br>
        g<br>
        i<br>
        s<br>
        t<br>
        r<br>
        a<br>
        t<br>
        i<br>
        o<br>
        n</td>
        <td colspan="3" ></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td colspan="2" rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-37" target="_blank">Parallel Sessions 10</a><br>
          (08:30-09:30)</td>
        <td rowspan="2" ></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td colspan="2" class="type-break">Break</td>
        <td  class="type-Research">Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" rowspan="2" class="type-keynote"><a href="/2026/program/keynote-speakers/#link03">Keynote 3</a><br>
        (10:00-11:00)</td>
        <td rowspan="6"></td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
        <td colspan="2" class="type-break">Break </td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
        <td colspan="2" rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-41" target="_blank">Parallel Sessions 11</a><br>
          (11:30-12:30)</td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td colspan="2" rowspan="3" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
        <td rowspan="2" class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td colspan="2" rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-45" target="_blank">Parallel Sessions 12</a><br>
          (14:00-15:00)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="2" class="type-Parallel"><a href="https://ieeevr.org/2026/program/papers/#session-49" target="_blank">Parallel Sessions 13</a><br>
          (15:00-16:00)</td>
        <td rowspan="3" class="type-workshop"><a href="https://ieeevr.org/2026/program/panels/">Panel Session</a><br>
          (15:00-16:30)</td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td class="type-break">Break</td>
        <td rowspan="2" class="type-Research">Research Demos, 3DUI Contest Demos, Posters, <br>
        XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td colspan="2" rowspan="3" class="type-Welcome">Closing & Awards <br>
          (16:30-17:30)</td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
        <td rowspan="2" ></td>
      </tr>
      <tr>
        <td class="time-col">17:30</td>
      </tr>
    </tbody>
  </table>
</div>
