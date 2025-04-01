<h1 align="center">안녕하세요 👋 김민석입니다</h1>
<h3 align="center">열정적인 퍼블리셔 김민석의 포트폴리오입니다</h3>
 👋 Welcome to My GitHub Portfolio!

안녕하세요! 저는 김민석입니다.
이 GitHub에는 제가 개발한 프로젝트와 학습한 내용을 정리해두었습니다.
주로 HTML, CSS, JavaScript, jQuery 등을 활용한 웹 퍼블리싱 작업을 진행하며,
웹 페이지의 디자인, 반응형 웹 구현, 접근성 향상, 그리고 최신 웹 기술을 적용하는 데 관심이 많습니다. 

## 🔥 주요 프로젝트  
아래 프로젝트를 통해 저의 개발 역량을 확인하실 수 있습니다.
<br>
### **1️⃣ 리액트 가계부**  
- 🔭 **리액트 가계부** [개발중인 React 가계부 앱/웹 Demo 보기](http://popola1.dothome.co.kr/)

- 🌱 리액트 가계부 - **2명으로 팀을 이루어 React를 활용하여 가계부 웹을 만들었습니다.**
  - 가계 수입/지출을 관리할 수 있는 웹 애플리케이션입니다.  
Firebase를 이용한 CRUD 기능으로 수입, 지출을 등록/등록된 기록을 클릭하면 상세보기와 수정, 삭제가 가능합니다,<br>
실시간 데이터 저장 및 동기화, 차트 기반 시각화, Excel 내보내기, 메모를 기준으로 검색등 기능을 포함하고 있습니다.
  <br>
- **프로젝트 개요:**
  - 이 프로젝트는 개인의 수입과 지출을 효과적으로 관리할 수 있는 "가계부 웹 애플리케이션"입니다. 사용자는 수입과 지출을 등록하고, 월별 통계를 확인하며, 거래 내역을 검색 및 필터링할 수 있습니다. 또한, Firebase를 활용한 실시간 데이터 저장 및 관리, 그리고 ChatGPT API를 이용한 금융 조언 기능을 제공합니다.
- **프로젝트 목적:**
  - 개인이 자신의 재정 상태를 한눈에 파악할 수 있도록 시각화된 데이터를 제공

  - 다양한 필터 및 검색 기능을 통해 원하는 거래 내역을 쉽게 찾을 수 있도록 구현

  - Firebase를 활용한 실시간 동기화를 통해 여러 기기에서 동일한 데이터를 사용할 수 있도록 지원

  - AI(ChatGPT API)를 활용하여 사용자의 소비 패턴을 분석하고 금융 조언을 제공
- **주요기능:**
  - 수입/지출 등록 : 손쉽게 수입과 지출을 추가하고 관리
  - 거래 기록 보기 : 거래 내역을 날짜별로 확인 가능
  - 수입/지출 수정 : 수입,지출의 내용을 삭제하거나 수정하여 저장
  - 월별 수입/지출 현황 표시 : 월별 수입,지출 통계 제공
  - 수입/지출 그래프 및 차트 : 사용자가 쉽게 이해할 수 있도록 시각적 데이터 제공
  - 검색/필터 기능 : 특정 거래 내역을 빠르게 찾을 수 있는 기능
  - 엑셀파일 출력 기능 : 수입, 지출 내용을 엑셀파일로 출력 가능
  - Chat GPT API : 사용자가 물어보는 질문에 대해 실시간으로 자동 응답.
  - Firebase Realtime : 실시간 데이터 저장 및 동기화<br>

- 🛠 **사용 기술:**
  - React, Firebase  
  - HTML, CSS, Recharts 라이브러리 
  - OpenAI API (ChatGPT 연동)
- 🌱 **리액트 가계부 React 코드** [코드 보기](https://github.com/kimminseock/Team-Project-Portfolio.git)
- 🌱 **리액트 가계부 소개 및 개발 담당 역할 소개 PDF** [PDF 보기](https://github.com/kimminseock/ReactTeamProject_pdf.git)<br>
- 🌱 **리액트 가계부 나의 기여도**
1. 화면 구성 및 기능 개발 (React):

   - React를 이용해 웹페이지 화면을 만들고, 데이터를 쉽게 입력할 수 있도록 구현

   - useState, useEffect를 사용해 화면이 자동으로 바뀌도록 설정

2. 데이터 저장 및 관리 (Firebase):

   - Firebase를 이용해 사용자의 수입/지출 기록을 저장하고 불러오는 기능 개발

3. 데이터 시각화 및 검색 기능:

   - Recharts 라이브러리를 이용해 월별 수입/지출을 그래프로 표시

   - 원하는 내역을 쉽게 찾을 수 있도록 검색 및 필터 기능 구현

4. ChatGPT API 연동:

   -  사용자의 소비 습관을 분석하고 간단한 조언을 제공하는 기능 개발

- 🌱 **리액트 가계부 문제 해결 과정**
1. 실시간 데이터 업데이트 문제

   문제: Firebase에서 데이터를 가져올 때 화면이 늦게 바뀌는 문제가 있었음

   해결: useEffect와 Firebase의 onValue 기능을 사용해 데이터를 바로 반영하도록 수정

2. 검색 속도 느림 문제

   문제: 모든 데이터를 한 번에 불러온 후 필터링을 적용하는 방식에서, 필요한 데이터만 가져오도록 쿼리 최적화

   해결: Firebase의 orderByChild와 equalTo 기능을 사용해 필요한 데이터만 가져오도록 수정

3. API 응답 속도 문제

   문제: ChatGPT API를 호출할 때 시간이 오래 걸리는 문제가 있었음

   해결: 최근 요청한 데이터를 저장해두고, 같은 질문이면 캐시된 데이터를 먼저 보여주도록 개선   

 ### **2️⃣ 포트폴리오 웹사이트**
  
- 🔭 **제빵 만드는 방법 소개 사이트** [반응형 제빵 만드는 방법 소개 사이트 보기](http://popola1.dothome.co.kr/bread/bakery.html)

- 🌱 제빵 만드는 방법 소개 사이트 - **생성형 AI 이미지를 활용하여 빵을 만드는 방법을 소개하는 사이트입니다.**
 - **설명**:<br>
  이 프로젝트는 생성형 AI 이미지를 활용하여 다양한 빵의 제작 방법을 소개하는 웹사이트입니다.<br> 
  **메인 페이지와 서브 페이지에서 CSS와 JavaScript 애니메이션을 각각 분리하여 활용**함으로써,<br> 
  퍼블리셔로서 애니메이션 구현 방식의 다양성과 효율성을 고려한 설계를 보여주고자 했습니다.<br>
- 🌱 **제빵 만드는 방법 소개 사이트 코드** [코드 보기](https://github.com/kimminseock/Personal-Portfolio.git)
- **기능**:
  - 슬라이드 애니메이션: 첫 페이지의 화살표나 오른쪽 밑에 있는 썸네일을 클릭하면 슬라이드 애니메이션 제공
  - 더 알아보기 버튼: 더 알아보기 버튼을 클릭하면 빵 만드는 방법 소개하는 페이지로 이동
  - 반응형 디자인: 다양한 화면 크기에서 최적화된 사용자 경험 제공
  - 생성형 AI 이미지: 빵 만들기 과정을 보여주는 AI 생성 이미지 사용
  - JavaScript 활용: 사용자와의 상호작용을 위한 동적 콘텐츠 처리
- **기술 포인트:**
  - 🧩 **메인 페이지**: `@keyframes` 기반의 CSS 애니메이션 사용  
    → 텍스트 등장/사라짐 효과, 슬라이드 전환, 썸네일 효과 등 모두 CSS로 표현  
    → JavaScript는 `.next`, `.prev` 클래스를 토글하여 **애니메이션을 트리거**하는 역할만 수행
  - ⚙️ **서브 페이지**:  
    - 이미지의 **흑백 → 컬러 전환**을 Web Animation API(`.animate()`)를 활용해 동적으로 구현  
    - `IntersectionObserver` 및 스크롤 이벤트를 사용하여 요소가 화면에 들어올 때 부드럽게 등장  
    - 모바일 메뉴 전개/닫힘은 JavaScript로 스타일 직접 제어
- **웹 접근성 및 퍼블리셔 관점 고려 사항:**
  - HTML5 시멘틱 태그를 적극 활용한 마크업  
  - CSS 미디어 쿼리 기반 반응형 웹 디자인 구현  
  - 크롬, 엣지 등 주요 브라우저에서 테스트 완료 (크로스 브라우징 고려)
- 🛠 **사용 기술:**  
  - HTML5, CSS3 (애니메이션 및 반응형), JavaScript (Vanilla), Web Animation API

 ### **3️⃣ 포트폴리오 웹사이트**

 - 🔭 **e_book 창작 사이트** [개발중인 e_book 사이트 보기](http://popola1.dothome.co.kr/e_book/index.html)

- 🌱 e_book 사이트 - **e_book의 창작 사이트입니다.**
- **설명**:<br>
  e-book 프로젝트는 퍼블리싱뿐 아니라 **다양한 웹 인터랙션 기능을 구현한 복합형 웹사이트**입니다.<br>  
  특히 JavaScript, jQuery, Swiper.js, GSAP, AOS 등 여러 라이브러리와 커스텀 로직을 함께 활용하여<br>  
  **실제 서비스 환경에 가까운 사용자 경험**을 구현하였습니다.
- **주요 스크립트 기능:**
  - 🔁 커스텀 메인 슬라이드: jQuery 기반 `.animate()` 슬라이더 + 버튼으로 직접 제어
  - 🧭 카테고리 필터링: `.click()` 이벤트로 콘텐츠 영역 분리 + AOS 애니메이션 재실행
  - 📚 다양한 Swiper 슬라이드:  
    - 기본형, Coverflow, Cards 효과 적용  
    - 반응형으로 자동 정렬, 브레이크포인트 기반 콘텐츠 전환
  - ✨ AOS: 스크롤 등장 애니메이션(`fade-up`, `fade-right`, `fade-up-right`)
  - 🎨 GSAP + ScrollTrigger: `.bg` 영역 스크롤에 따른 **색상 전환 효과**
  - ⌨️ 타이핑 효과: 책 소개 영역에 **문장 순차 출력 인터랙션**
- 🌱 **e_book 사이트 코드** [코드 보기](https://github.com/kimminseock/e-book)
- 🛠 **사용 기술:**
  - HTML5, CSS3, JavaScript, jQuery, Swiper.js, AOS, GSAP, ScrollTrigger
  
### **4️⃣ To Do List 웹앱 (Vanilla JS + LocalStorage 완전 구현)**

  - 🔭 **Todolist 웹사이트** [Todolist 웹사이트 보기](http://popola1.dothome.co.kr/to_do_list/index.html)
  - 🌱 CRUD를 기반으로 만든 Todolist 웹사이트 - **Todolist 반응형 웹사이트입니다.**
  -  **설명**:<br>
  이 프로젝트는 HTML, CSS, 그리고 순수 JavaScript만을 사용하여 만든 **할 일 관리 웹앱**입니다.  
  특히 `localStorage`를 활용하여 새로고침 후에도 데이터가 유지되며, **실제 서비스에 가까운 기능 구현**을 목표로 제작하였습니다.
  - **기능 구현 내용 (CRUD 완비):**
    - ✏️ **할 일 추가 (Create)**: 입력 필드에서 작성 후 추가
    - ✅ **목록 불러오기 (Read)**: `DOMContentLoaded` 시점에 저장된 항목 자동 출력
    - 🔁 **선택 삭제 (Update/Delete)**: 체크된 항목만 삭제 가능
    - 🧹 **전체 삭제 / 마지막 항목 삭제**: 다양한 상황에 맞춘 삭제 기능 구현
    - 💾 **로컬스토리지 저장 기능**: 새로고침 후에도 데이터가 유지됨
- 🌱 **Todolist 웹사이트 코드** [코드 보기](https://github.com/kimminseock/Todolist)
- - 🛠 **사용 기술:**
  - HTML5, CSS3, JavaScript, Web Storage API (`localStorage`)
    
- 📫 **연락받을 이메일 주소:** popola22@naver.com
- 📫 **연락받을 번호:** 010-6656-7464

---

## 웹퍼블리셔 기술 스택:

<table>
  <tr>
    <td align="center"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="40"><br>피그마</td>
    <td align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="40"><br>HTML5</td>
    <td align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="40"><br>CSS3</td>
    <td align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40"><br>JavaScript</td>
    <td align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40"><br>React</td>
    <td align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/jquery/jquery-original.svg" width="40"><br>jQuery</td>
    <td align="center"><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" width="40"><br>Firebase</td>
  </tr>
</table>








