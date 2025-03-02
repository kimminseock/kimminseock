<h1 align="center">안녕하세요 👋 김민석입니다</h1>
<h3 align="center">열정적인 프론트엔드 개발자</h3>
 👋 Welcome to My GitHub Portfolio!

안녕하세요! 저는 프론트엔드 개발을 전문으로 하는 김민석입니다.  
이 GitHub에는 제가 개발한 프로젝트와 학습한 내용을 정리해두었습니다.  
주로 **React, JavaScript, HTML, CSS** 등을 활용한 프로젝트를 진행하며,  
API 연동, 데이터 시각화, Firebase 및 기타 최신 웹 기술을 적용하는 데 관심이 많습니다.  

## 🔥 주요 프로젝트  
아래 프로젝트를 통해 저의 개발 역량을 확인하실 수 있습니다.
<br>
### **1️⃣ 리액트 가계부**  
- 🔭 **리액트 가계부** [개발중인 React 가계부 앱/웹 Demo](http://popola1.dothome.co.kr/)

- 🌱 리액트 가계부 - **2명으로 팀을 이루어 React를 활용하여 가계부 웹을 만들었습니다.**
  - 가계 수입/지출을 관리할 수 있는 웹 애플리케이션입니다.  
Firebase를 이용한 **CRUD 기능으로 수입, 지출을 등록/등록된 기록을 클릭하면 상세보기와 수정, 삭제가 가능합니다**,<br>
**실시간 데이터 저장 및 동기화**, **차트 기반 시각화**, **Excel 내보내기**, **메모를 기준으로 검색**등 기능을 포함하고 있습니다.
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
1. 프론트엔드 개발 (React):

   - React를 사용하여 사용자 친화적인 UI/UX를 설계 및 구현

   - 상태 관리 (useState, useEffect 등)를 활용하여 데이터 변경 시 동적으로 반영되도록 처리

2. 실시간 데이터베이스 연동 (Firebase):

   - Firebase Realtime Database를 이용해 데이터를 실시간 저장 및 불러오기 기능 구현

3. 데이터 시각화 및 필터링 기능:

   - Chart.js를 활용하여 월별 수입/지출 데이터를 그래프 형태로 제공

   - 사용자가 원하는 데이터를 쉽게 찾을 수 있도록 검색 및 필터 기능 구현

4. ChatGPT API 연동:

   -  사용자의 소비 패턴을 분석하고 맞춤형 금융 조언을 제공하는 기능 구현

- 🌱 **리액트 가계부 문제 해결 과정**
1. 실시간 동기화 문제

   - Firebase에서 데이터를 가져올 때, 비동기 처리 문제로 인해 UI가 정상적으로 업데이트되지 않는 이슈 발생

   - useEffect와 Firebase의 onValue 리스너를 활용하여 상태를 지속적으로 업데이트하도록 수정

2. 데이터 필터링 속도 저하

  - 모든 데이터를 한 번에 불러온 후 필터링을 적용하는 방식에서, 필요한 데이터만 가져오도록 쿼리 최적화

  - Firebase의 orderByChild와 equalTo를 조합하여 검색 성능 개선

3. API 응답 속도 지연

  - ChatGPT API를 연동할 때 응답 속도가 느려 사용자 경험이 저하됨

  - API 요청을 최소화하기 위해 로컬 스토리지에 최근 응답을 캐싱하고, 동일한 요청이 발생하면 캐싱된 데이터를 우선 제공   

  <br>
  <br>
- ### **2️⃣ 포트폴리오 웹사이트**
  
- 🔭 **제빵 만드는 방법 소개 사이트** [개발중인 반응형 제빵 만드는 방법 소개 Demo](http://popola1.dothome.co.kr/bread/bakery.html)

- 🌱 제빵 만드는 방법 소개 사이트 - **생성형 AI 이미지를 활용하여 빵을 만드는 방법을 소개하는 사이트입니다.**
 - **설명**:<br>
  이 프로젝트는 **바닐라 JavaScript**를 사용하여, 빵을 만드는 방법을 소개하는 웹사이트입니다. 또한,
  **생성형 AI 이미지**를 사용하여 시각적으로 매력적인 콘텐츠를 제공하며, **반응형 웹 디자인**을 통해
  다양한 디바이스에서 최적화된 환경을 제공합니다.<br>
  빵 슬라이드 화면에서 **더 알아보기 버튼을 클릭**하면 해당 빵을 만드는 방법을 알려주는 사이트로 이동합니다.
- 🌱 **제빵 만드는 방법 소개 사이트 코드** [코드 보기](https://github.com/kimminseock/Personal-Portfolio.git)
- **기능**:
  - 슬라이드 애니메이션: 첫 페이지의 화살표나 오른쪽 밑에 있는 썸네일을 클릭하면 슬라이드 애니메이션 제공
  - 반응형 디자인: 다양한 화면 크기에서 최적화된 사용자 경험 제공
  - 생성형 AI 이미지: 빵 만들기 과정을 보여주는 AI 생성 이미지 사용
  - JavaScript 활용: 사용자와의 상호작용을 위한 동적 콘텐츠 처리
- 🛠 **사용 기술:**  
  - HTML, CSS, JavaScript
- 📫 **연락받을 이메일 주소:** popola22@naver.com
- 📫 **연락받을 번호:** 010-6656-7464

---

## 웹퍼블리셔 기술 스택:

| <p align="center"><img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" width="40"><br>피그마</p> | <p align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" width="40"><br>HTML5</p> | <p align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" width="40"><br>CSS3</p> | <p align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" width="40"><br>JavaScript</p> | <p align="center"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" width="40"><br>React</p> | <p align="center"><img src="https://www.vectorlogo.zone/logos/jquery/jquery-icon.svg" width="40"><br>jQuery</p> | <p align="center"><img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" width="40"><br>Firebase</p> |
|--------|------|------|------------|------|---------|--------|






