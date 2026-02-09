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
    font-size: 1.3em;
    color: #066569;
    border-bottom: 1px solid #066569;
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
	background-color: #F2F2F2;
	font-weight: bold;
	color: #333;
	font-size:0.5rem
}
.reg-col {
	background-color: #D9D9D9;
	font-weight: bold;
	color: #444;
}
/* 세션 타입별 컬러 */
.type-break {
	background-color: #f3f3f3;
	color: #000;
} /* 휴식 */
.type-lunch {
	background-color: #f3f3f3;
	color: #000;
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
	background-color: #e9d9e5;
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
.type-Welcome {
	background-color: #FFD9DA ;
	color: #000;
}

.type-Paralle {
	background-color: #E2E2C7  ;
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
        <td colspan="3" class="reg-col">Registration</td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td rowspan="9" class="type-workshop">Workshops<br>
          (08:30-12:30)</td>
        <td rowspan="3" class="type-tuto">Tutorials<br>
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
        <td rowspan="3" class="type-tuto">Tutorials<br>
          (10:30-12:00)</td>
        <td rowspan="3" class="type-doct">Doctoral Consortium</td>
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
        <td colspan="3" rowspan="3" class="type-lunch">Lunch (Not Catered)</td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td rowspan="8" class="type-workshop">Workshops<br>
          (14:00-18:00)</td>
        <td rowspan="3" class="type-tuto">Tutorials<br>
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
        <td rowspan="3" class="type-tuto">Tutorials<br>
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
<h3>Day 2: Mar. 22 (Sun)</h3>
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
      <td colspan="3" class="reg-col">Registration</td>
    </tr>
    <tr>
      <td class="time-col">08:30</td>
      <td rowspan="9" class="type-workshop">Workshops<br>
        (08:30-12:30)</td>
      <td rowspan="3" class="type-tuto">Tutorials<br>
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
      <td rowspan="3" class="type-tuto">Tutorials<br>
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
      <td colspan="3" rowspan="3" class="type-lunch">Lunch (Not Catered)</td>
    </tr>
    <tr>
      <td class="time-col">13:00</td>
    </tr>
    <tr>
      <td class="time-col">13:30</td>
    </tr>
    <tr>
      <td class="time-col">14:00</td>
      <td rowspan="9" class="type-workshop">Workshops<br>
        (14:00-18:00)</td>
      <td rowspan="3" class="type-tuto">Tutorials<br>
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
      <td rowspan="3" class="type-tuto">Tutorials<br>
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
    </tr>
    </tbody>
  <tbody>
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
        <td rowspan="38" class="reg-col">R<br>
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
        <td colspan="2" class="reg-col">Registration</td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td rowspan="2" class="type-keynote">Opening & Awards<br>
          (08:30-09:30)</td>
        <td rowspan="2" ></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td colspan="2" class="type-break">Break / Research Demos, Posters</td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td rowspan="2" class="type-keynote">Keynote 1<br>
          (10:00-11:00)</td>
        <td rowspan="2">&nbsp;</td>
      </tr>
      <tr>
        <td class="time-col">10:30</td>
      </tr>
      <tr>
        <td class="time-col">11:00</td>
        <td class="type-break">Break (Catered)</td>
        <td class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">11:30</td>
        <td rowspan="2" class="type-keynote">Parallel Sessions 1<br>
          (11:30-12:30)</td>
        <td rowspan="3" ></td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td rowspan="2" class="time-col">12:30</td>
        <td rowspan="4" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td rowspan="3" class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td rowspan="2" class="type-keynote">Parallel Sessions 2<br>
          (14:00-15:00)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="2" class="type-keynote">Parallel Sessions 3<br>
          (15:00-16:00)</td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td class="type-break">Break</td>
        <td class="type-Research">Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td rowspan="2" class="type-keynote">Parallel Sessions 4<br>
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
<h3>Day 4: Mar. 24 (Tue)</h3>
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
        <td colspan="3" class="reg-col">Registration</td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td colspan="2" rowspan="2" class="type-keynote">Parallel Sessions 5<br>(08:30-09:30)</td>
        <td rowspan="2"></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td colspan="2" class="type-break">Break</td>
        <td>Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" rowspan="2" class="type-keynote">Keynote 2<br>
          (10:00-11:00)</td>
        <td rowspan="6">&nbsp;</td>
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
        <td colspan="2" rowspan="2" class="type-keynote">Parallel Sessions 6<br>
          (11:30-12:30)</td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td rowspan="2" class="time-col">12:30</td>
        <td colspan="2" rowspan="4" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td rowspan="3" class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td colspan="2" rowspan="2" class="type-keynote">Parallel Sessions 7<br>
          (14:00-15:00)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="2" class="type-keynote">Parallel Sessions 8<br>
          (15:00-16:00)</td>
        <td rowspan="2" class="type-workshop">Panel<br>
          (15:00-16:30)</td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td colspan="2" class="type-break">Break</td>
        <td>Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td colspan="2" rowspan="2" class="type-keynote">Parallel Sessions 9<br>
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
         <td rowspan="2" class="time-col">18:30</td>
      </tr>
      <tr>
        <td colspan="3" rowspan="6" class="type-Welcome">Gala Dinner<br>
          (18:30-21:00)</td>
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
<h3>Day 5: Mar. 25 (Wed)</h3>
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
        <td rowspan="34" class="reg-col">R<br>
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
        <td colspan="3" class="reg-col">Registration</td>
      </tr>
      <tr>
        <td class="time-col">08:30</td>
        <td colspan="2" rowspan="2" class="type-keynote">Parallel Sessions 10<br>
          (08:30-09:30)</td>
        <td rowspan="2" ></td>
      </tr>
      <tr>
        <td class="time-col">09:00</td>
      </tr>
      <tr>
        <td class="time-col">09:30</td>
        <td colspan="2" class="type-break">Break</td>
        <td  class="type-Research">Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">10:00</td>
        <td colspan="2" rowspan="2" class="type-keynote">Keynote 3<br>
          (10:00-11:00)</td>
        <td rowspan="6">&nbsp;</td>
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
        <td colspan="2" rowspan="2" class="type-keynote">Parallel Sessions 11<br>
          (11:30-12:30)</td>
      </tr>
      <tr>
        <td class="time-col">12:00</td>
      </tr>
      <tr>
        <td rowspan="2" class="time-col">12:30</td>
        <td colspan="2" rowspan="4" class="type-lunch">Lunch (Not Catered) </td>
      </tr>
      <tr>
        <td rowspan="3" class="type-Research" >Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">13:00</td>
      </tr>
      <tr>
        <td class="time-col">13:30</td>
      </tr>
      <tr>
        <td class="time-col">14:00</td>
        <td colspan="2" rowspan="2" class="type-keynote">Parallel Sessions 12<br>
          (14:00-15:00)</td>
        <td rowspan="4" ></td>
      </tr>
      <tr>
        <td class="time-col">14:30</td>
      </tr>
      <tr>
        <td class="time-col">15:00</td>
        <td rowspan="2" class="type-keynote">Parallel Sessions 13<br>
          (15:00-16:00)</td>
        <td rowspan="3" class="type-workshop">Panel Session<br>
          (15:00-16:30)</td>
      </tr>
      <tr>
        <td class="time-col">15:30</td>
      </tr>
      <tr>
        <td class="time-col">16:00</td>
        <td class="type-break">Break</td>
        <td class="type-Research">Research Demos, 3DUI Contest Demos, Posters, XR Gallery</td>
      </tr>
      <tr>
        <td class="time-col">16:30</td>
        <td colspan="2" rowspan="3" class="type-Welcome">Closing & Awards <br>
          (16:30-17:30)</td>
        <td rowspan="3" ></td>
      </tr>
      <tr>
        <td class="time-col">17:00</td>
      </tr>
      <tr>
        <td class="time-col">17:30</td>
      </tr>
    </tbody>
  </table>
</div>




