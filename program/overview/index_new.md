---
layout: ieeevr-default
title: "Program Overview"
subtitle: "IEEE VR 2026"
title_separator: "|"
---

<style>
/* 1. 폰트 크기 반응형 적용 (최소 9px ~ 최대 11px) */

body {
	font-family: "Malgun Gothic", "Segoe UI", sans-serif;
	font-size: clamp(9px, 2.5vw, 11px);
	margin: 20px;
}
h3 {
	color: #2F5597;
	border-bottom: 2px solid #2F5597;
	padding-bottom: 5px;
	margin-top: 40px;
}
/* 2. 가로 스크롤을 위한 래퍼(Wrapper) 스타일 정의 */
.table-scroll {
	width: 100%;
	overflow-x: auto;       /* 내용이 넘치면 스크롤 생성 */
	margin-bottom: 40px;    /* 표 아래 여백 */
	-webkit-overflow-scrolling: touch; /* 모바일 부드러운 스크롤 */
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
}
/* 컬럼 스타일 */
.time-col {
	background-color: #F2F2F2;
	font-weight: bold;
	color: #333;
}
.reg-col {
	background-color: #D9D9D9;
	font-weight: bold;
	writing-mode: vertical-rl;
	transform: rotate(180deg);
	color: #444;
}
/* 세션 타입별 컬러 */
.type-break {
	background-color: #E2EFDA;
	color: #385723;
} /* 휴식 */
.type-lunch {
	background-color: #FFF2CC;
	color: #9C5700;
} /* 점심 */
.type-keynote {
	background-color: #E4DFEC;
	color: #5F497A;
	font-weight: bold;
} /* 키노트/오프닝 */
.type-social {
	background-color: #FCE4D6;
	color: #974806;
	font-weight: bold;
} /* 리셉션/디너 */
.type-workshop {
	background-color: #FFE6F9;
	color: #000;
} /* 워크숍/세션 */
.type-empty {
	background-color: #FFFFFF;
}
.type-tuto {
	background-color: #FFF8EA;
	color: #000;
}
.type-doct {
	background-color: #E6EEFF;
	color: #000;
}
.type-Future {
	background-color: #FFE8E8;
	color: #000;
}
.type-Research {
	background-color: #EEFFE8;
	color: #000;
}
</style>

<h3>Day 1: Mar. 21 (Sat)</h3>
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
      <tr>
        <th colspan="5" class="day-header">Day 1_Mar. 21 (Sat)</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td class="time-col">08:00</td>
        <td rowspan="60" class="reg-col">Registration</td>
        <td colspan="3" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
        <td colspan="3" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td rowspan="18" class="type-workshop">Workshops<br>
          (08:30-12:30)</td>
        <td rowspan="6" class="type-tuto">Tutorials<br>
          (08:30-10:00)</td>
        <td rowspan="6" class="type-doct">Doctoral Consortium</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" rowspan="2" class="type-break">Break (Catered)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
        <td rowspan="6" class="type-tuto">Tutorials<br>
          (10:30-12:00)</td>
        <td rowspan="6" class="type-doct">Doctoral Consortium</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
        <td colspan="2" rowspan="2" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td colspan="3" rowspan="6" class="type-lunch">Lunch (Not Catered)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td rowspan="16" class="type-workshop">Workshops<br>
          (14:00-18:00)</td>
        <td rowspan="6" class="type-tuto">Tutorials<br>
          (14:00-15:30)</td>
        <td rowspan="6" class="type-doct">Doctoral Consortium</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
        <td colspan="2" rowspan="2" class="type-break">Break (Catered)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td rowspan="6" class="type-tuto">Tutorials<br>
          (16:00-17:30)</td>
        <td rowspan="6" class="type-doct">Doctoral Consortium</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">17:30</td>
        <td colspan="2" rowspan="2" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">18:00</td>
        <td colspan="3" class="type-empty"></td>
      </tr>
    </tbody>
  </table>
</div>
<h3>Day 2: Mar. 22 (Sun)</h3>
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
        <td rowspan="60" class="reg-col">Registration</td>
        <td colspan="3" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
        <td colspan="3" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td rowspan="18" class="type-workshop">Workshops<br>
          (08:30-12:30)</td>
        <td rowspan="6" class="type-tuto">Tutorials<br>
          (08:30-10:00)</td>
        <td rowspan="6" class="type-Future">Future Faculty Forum</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" rowspan="2" class="type-break">Break (Catered)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
        <td rowspan="6" class="type-tuto">Tutorials<br>
          (10:30-12:00)</td>
        <td rowspan="6" class="type-Future">Future Faculty Forum</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
        <td colspan="2" rowspan="2" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td colspan="3" rowspan="6" class="type-lunch">Lunch (Not Catered)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td rowspan="16" class="type-workshop">Workshops<br>
          (14:00-18:00)</td>
        <td rowspan="6" class="type-tuto">Tutorials<br>
          (14:00-15:30)</td>
        <td rowspan="6" class="type-Future">Future Faculty Forum</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
        <td colspan="2" rowspan="2" class="type-break">Break (Catered)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td rowspan="6" class="type-tuto">Tutorials<br>
          (16:00-17:30)</td>
        <td rowspan="6" class="type-Future">Future Faculty Forum</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">17:30</td>
        <td colspan="3" rowspan="4" class="type-social">Welcome Reception<br>
          (17:30-19:30)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">18:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
    </tbody>
  </table>
</div>
<h3>Day 3: Mar. 23 (Mon)</h3>
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
        <td rowspan="62" class="reg-col">Registratio</td>
        <td colspan="2" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td rowspan="4" class="type-keynote">Opening & Awards<br>
          (08:30-09:30)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td colspan="2" rowspan="2" class="type-break">Break / Research Demos, Posters</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td rowspan="4" class="type-keynote">Keynote 1<br>
          (10:00-11:00)</td>
        <td rowspan="4">&nbsp;</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
        <td rowspan="2" class="type-break">Break (Catered)</td>
        <td rowspan="2" class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
        <td rowspan="4" class="type-workshop">Parallel Sessions 1<br>
          (11:30-12:30)</td>
        <td rowspan="5" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td rowspan="6" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td class="time-col"></td>
        <td rowspan="5" class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td rowspan="4" class="type-workshop">Parallel Sessions 2<br>
          (14:00-15:00)</td>
        <td rowspan="8" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="4" class="type-workshop">Parallel Sessions 3<br>
          (15:00-16:00)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td rowspan="2" class="type-break">Break</td>
        <td rowspan="2">Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td rowspan="4" class="type-workshop">Parallel Sessions 4<br>
          (16:30-17:30)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
        <td colspan="2" rowspan="12" class="type-workshop">Welcome Reception<br>
          (17:30-19:30)</td>
      </tr>
      <tr>
        <td class="time-col">17:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">18:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">19:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">19:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
    </tbody>
  </table>
</div>
<h3>Day 4: Mar. 24 (Tue)</h3>
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
        <td rowspan="71" class="reg-col">Registratio</td>
        <td colspan="3" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td colspan="2" rowspan="4" class="type-keynote">Parallel Sessions 5<br>(08:30-09:30)</td>
        <td rowspan="4"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td colspan="2" rowspan="2" class="type-break">Break</td>
        <td rowspan="2">Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" rowspan="4" class="type-keynote">Keynote 2<br>
          (10:00-11:00)</td>
        <td rowspan="11">&nbsp;</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
        <td colspan="2" rowspan="2" class="type-break">Break </td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
        <td colspan="2" rowspan="4" class="type-workshop">Parallel Sessions 6<br>
          (11:30-12:30)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td colspan="2" rowspan="6" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td class="time-col"></td>
        <td rowspan="5"class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td colspan="2" rowspan="4" class="type-workshop">Parallel Sessions 7<br>
          (14:00-15:00)</td>
        <td rowspan="8" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="4" class="type-workshop">Parallel Sessions 8<br>
          (15:00-16:00)</td>
        <td rowspan="4" class="type-workshop">Panel<br>
          (15:00-16:30)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td colspan="2" rowspan="2" class="type-break">Break</td>
        <td rowspan="2">Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td colspan="2" rowspan="4" class="type-workshop">Parallel Sessions 9<br>
          (16:30-17:30)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
        <td colspan="3" rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col">17:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">18:30</td>
        <td colspan="3" rowspan="17" class="type-workshop">Gala Dinner<br>
          (18:30-21:00)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">19:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">19:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">20:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">20:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">21:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
    </tbody>
  </table>
</div>
<h3>Day 5: Mar. 25 (Wed)</h3>
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
        <td rowspan="50" class="reg-col">Registratio</td>
        <td colspan="3" class="type-empty"></td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td colspan="2" rowspan="4" class="type-keynote">Parallel Sessions 10<br>
          (08:30-09:30)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td colspan="2" rowspan="2" class="type-break">Break</td>
        <td rowspan="2">Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" rowspan="4" class="type-keynote">Keynote 3<br>
          (10:00-11:00)</td>
        <td rowspan="11">&nbsp;</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
        <td colspan="2" rowspan="2" class="type-break">Break </td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
        <td colspan="2" rowspan="4" class="type-workshop">Parallel Sessions 11<br>
          (11:30-12:30)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">12:30</td>
        <td colspan="2" rowspan="6" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td class="time-col"></td>
        <td rowspan="5" class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td colspan="2" rowspan="4" class="type-workshop">Parallel Sessions 12<br>
          (14:00-15:00)</td>
        <td rowspan="8" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="4" class="type-workshop">Parallel Sessions 13<br>
          (15:00-16:00)</td>
        <td rowspan="6" class="type-workshop">Panel Session<br>
          (15:00-16:30)</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td rowspan="2" class="type-break">Break</td>
        <td rowspan="2" class="type-Research">Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td colspan="2" rowspan="4" class="type-workshop">Closing & Awards <br>
          (16:30-17:30)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
        <td class="time-col"></td>
      </tr>
    </tbody>
  </table>
</div>

