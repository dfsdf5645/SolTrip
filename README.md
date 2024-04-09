<h1 align="center"> ✈ SolTrip - 2023 신한은행 해커톤 with SSAFY ✈  </h1>

<div>
  <h3>맞춤형 여행 예산 관리 플랫폼</h3>
</div>

<br/>

## 📅 기간

- **2023.09.01 ~ 2023.09.17(2주)**

<br/>

## 🔎 목차

1. <a href="#item-one">📖 프로젝트 개요</a>
1. <a href="#item-two">🛠️ 기술 스택</a>
1. <a href="#item-three">⚙️ 아키텍처</a>
1. <a href="#item-four">🗂️ 프로젝트 파일 구조</a>
1. <a href="#item-five">🖥 서비스 구현 화면</a>
1. <a href="#item-six">👥 팀원 소개</a>

<br/>


## 📖 프로젝트 개요

<a name="item-one"></a>

<div>

<strong>목표</strong>

- 사용자들이 보다 쉽게 여행 예산을 관리할 수 있도록 돕는 서비스
- 신한 은행 Open API를 활용하여 실시간 예산 관리
- 사용자들이 많이 결제한 장소 위주로 인기 장소 추천
- 여행을 마친 후 사용 예산 기록을 포트폴리오로 저장

</div>

<br/>

## 🛠️ 기술 스택

<a name="item-two"></a>

### 💻 IDE

![VSCode](https://img.shields.io/badge/VisualStudioCode-007ACC?style=for-the-badge&logo=VisualStudioCode&logoColor=white)
![IntelliJ](https://img.shields.io/badge/intellijidea-000000?style=for-the-badge&logo=intellijidea&logoColor=white)

<br/>

### 📱 Frontend

![React](https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![React-Query](https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![PWA](https://img.shields.io/badge/pwa-5A0FC8?style=for-the-badge&logo=pwa&logoColor=white)

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) 
![JavaScript](https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)

<br/>

### 💾 Backend

![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) 
![SpringBoot](https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white) 

![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=for-the-badge&logo=redis&logoColor=white) 
![PostgreSQL](https://img.shields.io/badge/mongoDB-47A248?style=for-the-badge&logo=MongoDB&logoColor=white)
![mysql](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=PostgreSQL&logoColor=white)

<br/>



### 🔃 DevOPS

![nginx](https://img.shields.io/badge/nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white)

<br/>

## ⚙️ 아키텍처

<a name="item-three"></a>

![image](https://github.com/SawSimE/SolTrip/assets/66519915/2250b17a-db90-4a57-871d-d8a57628168e)

<br/>

## 🗂️ 프로젝트 파일 구조

<a name="item-four"></a>

<details>
<summary>FrontEnd</summary>
  
```
📦src
 ┣ 📂Api
 ┃ ┣ 📜Api.js
 ┃ ┗ 📜pencil.png
 ┣ 📂assets
 ┃ ┣ 📜books.png
 ┃ ┣ 📜books3.png
 ┃ ┣ 📜cash.png
 ┃ ┣ 📜coffee.png
 ┃ ┣ 📜donut.png
 ┃ ┣ 📜gym.png
 ┃ ┣ 📜location.png
 ┃ ┣ 📜login.png
 ┃ ┣ 📜paperplane.png
 ┃ ┣ 📜pencil.png
 ┃ ┣ 📜pencil2.png
 ┃ ┣ 📜sad.png
 ┃ ┣ 📜sea.gif
 ┃ ┣ 📜spot.png
 ┃ ┗ 📜verify.png
 ┣ 📂components
 ┃ ┣ 📂budget
 ┃ ┃ ┣ 📜Popular.js
 ┃ ┃ ┣ 📜Popular.module.css
 ┃ ┃ ┣ 📜Report.js
 ┃ ┃ ┗ 📜Report.module.css
 ┃ ┣ 📂cash
 ┃ ┃ ┣ 📜CashorOCR.js
 ┃ ┃ ┣ 📜CashorOCR.module.css
 ┃ ┃ ┣ 📜CreateInPerson.js
 ┃ ┃ ┗ 📜CreateInPerson.module.css
 ┃ ┣ 📂common
 ┃ ┃ ┣ 📜Header.js
 ┃ ┃ ┗ 📜Header.module.css
 ┃ ┣ 📂login
 ┃ ┃ ┣ 📜TransferOne.js
 ┃ ┃ ┗ 📜TransferOne.module.css
 ┃ ┣ 📂main
 ┃ ┃ ┣ 📜BalanceSchedule.js
 ┃ ┃ ┣ 📜BalanceSchedule.module.css
 ┃ ┃ ┣ 📜Insurance.js
 ┃ ┃ ┣ 📜Insurance.module.css
 ┃ ┃ ┣ 📜PortBanner.js
 ┃ ┃ ┣ 📜PortBanner.module.css
 ┃ ┃ ┣ 📜shinhan.png
 ┃ ┃ ┗ 📜trip1.png
 ┃ ┣ 📂plan
 ┃ ┃ ┣ 📜backup.js
 ┃ ┃ ┣ 📜Back_Calendar.js
 ┃ ┃ ┣ 📜Back_SelectedDate.js
 ┃ ┃ ┣ 📜bbackup.js
 ┃ ┃ ┣ 📜Calendar.css
 ┃ ┃ ┣ 📜Calendar.js
 ┃ ┃ ┣ 📜DateList.js
 ┃ ┃ ┣ 📜DateList.module.css
 ┃ ┃ ┣ 📜SelectedDate.js
 ┃ ┃ ┣ 📜SelectedDate.module.css
 ┃ ┃ ┗ 📜TestCalendar.js
 ┃ ┣ 📂planBudget
 ┃ ┃ ┣ 📜CreateBudget.js
 ┃ ┃ ┣ 📜CreateBudget.module.css
 ┃ ┃ ┣ 📜EditBudget.js
 ┃ ┃ ┗ 📜UpdateBudget.module.css
 ┃ ┣ 📂popular
 ┃ ┃ ┣ 📜BackUpPopular.js
 ┃ ┃ ┣ 📜PopularSpots.js
 ┃ ┃ ┗ 📜PopularSpots.module.css
 ┃ ┗ 📂portfolio
 ┃ ┃ ┣ 📜Analysis.js
 ┃ ┃ ┣ 📜Analysis.module.css
 ┃ ┃ ┣ 📜Map.css
 ┃ ┃ ┣ 📜Map.js
 ┃ ┃ ┣ 📜Map.module.css
 ┃ ┃ ┣ 📜PortList.js
 ┃ ┃ ┗ 📜PortList.module.css
 ┣ 📂lib
 ┃ ┣ 📜PageBlock.js
 ┃ ┣ 📜PrivateRoute.js
 ┃ ┗ 📜PublicRoute.js
 ┣ 📂pages
 ┃ ┣ 📜Budget.js
 ┃ ┣ 📜Budget.module.css
 ┃ ┣ 📜Cash.js
 ┃ ┣ 📜Cash.module.css
 ┃ ┣ 📜CashCreate.js
 ┃ ┣ 📜CashCreate.module.css
 ┃ ┣ 📜Dutch.js
 ┃ ┣ 📜Dutch.module.css
 ┃ ┣ 📜Login.js
 ┃ ┣ 📜Login.module.css
 ┃ ┣ 📜login.png
 ┃ ┣ 📜MainPage.js
 ┃ ┣ 📜MainPage.module.css
 ┃ ┣ 📜Plan.js
 ┃ ┣ 📜Plan.module.css
 ┃ ┣ 📜PlanBudget.js
 ┃ ┣ 📜PlanBudget.module.css
 ┃ ┣ 📜PlanBudgetDetail.js
 ┃ ┣ 📜PlanDetail.js
 ┃ ┣ 📜PlanDetail.module.css
 ┃ ┣ 📜PopularPage.js
 ┃ ┣ 📜PopularPage.module.css
 ┃ ┣ 📜PortfolioDetail.js
 ┃ ┣ 📜PortfolioDetail.module.css
 ┃ ┣ 📜PortfolioPage.js
 ┃ ┣ 📜PortfolioPage.module.css
 ┃ ┣ 📜Transaction.css
 ┃ ┣ 📜Transaction.js
 ┃ ┣ 📜Transaction.module.css
 ┃ ┣ 📜TransactionDetail.js
 ┃ ┣ 📜TransactionDetail.module.css
 ┃ ┗ 📜UpdateBudget.js
 ┣ 📜App.css
 ┣ 📜App.js
 ┣ 📜App.test.js
 ┣ 📜index.css
 ┣ 📜index.js
 ┣ 📜logo.svg
 ┣ 📜reportWebVitals.js
 ┣ 📜service-worker.js
 ┣ 📜serviceWorkerRegistration.js
 ┣ 📜setupProxy.js
 ┗ 📜setupTests.js
```
  
</details>

<br/>

## 🖥️ 서비스 구현 화면

<a name="item-five"></a>

### 1. 랜딩 페이지 로그인
1.1 로그인 페이지

![image](https://github.com/SawSimE/SolTrip/assets/66519915/b9c7c050-e28f-4174-b65d-4b374964d697)

- 예금주 이름과 계좌번호를 통해서 로그인

1.2 본인인증

![image](https://github.com/SawSimE/SolTrip/assets/66519915/22e49162-41b7-4cb3-98b4-59b714f54257)

- 본인 계좌에 1원 송금을 통해서 본인 인증을 진행
  
<br/>

### 2. 메인화면

![image](https://github.com/SawSimE/SolTrip/assets/66519915/c1f9bf71-ccb0-4bf5-b17d-eb6cf8580c0f)
<img src="https://github.com/gayong/SolTrip/assets/122499571/ec96b4ad-da38-4ff0-a629-85150435bd14" width="325"/>

(좌) 등록된 여행 일정이 없을 때 / (우) 등록된 여행 일정이 있을 때

<br/>

### 3. 여행 일정 등록

3.1 여행 날짜 등록

![image](https://github.com/SawSimE/SolTrip/assets/66519915/fae77547-262d-49e7-8f82-72ae608269ab)

- 여행 일정 날짜를 등록

3.2 여행 예산 등록

![image](https://github.com/SawSimE/SolTrip/assets/66519915/7dabb7c3-dd3e-470a-8c14-5c1601bd4491)
![image](https://github.com/SawSimE/SolTrip/assets/66519915/1b4ff0ab-a1a8-4591-93af-c6fcaf4ca98e)
![image](https://github.com/SawSimE/SolTrip/assets/66519915/982eb08e-99df-4132-8145-4b83eca49bea)

- 일자별로 카테고리와 예상 예산 금액을 입력하여 예산을 등록

<br/>

### 4. 여행 예산 분석

4.1 여행 예산 분석

![image](https://github.com/SawSimE/SolTrip/assets/66519915/8c10cee1-fa5d-4c27-a04d-ff497de04f2b)

- 오늘 날짜의 여행 예산에서 사용 금액과 카테고리 별 퍼센트를 표시
  
<br/>


### 5. 인기 장소 추천

5.1 인기 장소 추천

<img src="https://github.com/gayong/SolTrip/assets/122499571/a3cd7135-ba9f-4154-99a8-133ec99973a7" width="325"/> 
<img src="https://github.com/SawSimE/SolTrip/assets/66519915/e95bc924-49b4-47df-b9aa-95be21419411" width="325"/> 


- 현재 내 위치를 GPS로 파악해 인근 지역 내 다른 사용자들의 결제 내역이 가장 많은 순으로 표시 (카테고리별 분류)
  
<br/>

### 6. 거래 내역 확인 및 정산

6.1 거래 내역

![image](https://github.com/SawSimE/SolTrip/assets/66519915/5967b5dd-cacb-45f1-8dc5-2628e669ccef)

- 여행 중 사용한 카드/현금 거래 내역 표시

6.2. 현금 기록하기

<img src="https://github.com/gayong/SolTrip/assets/122499571/f6754b36-3dac-42e5-a197-4702c6223e77" width="325"/>

- 현금의 경우 직접 기록하기 가능

6.3. 거래 상세내역

<img src="https://github.com/gayong/SolTrip/assets/122499571/42ddbeb3-626d-4d57-b813-0a7a13a0969a" width="325"/>

- 거래 내역 선택 시 뜨는 상세 내역

6.4 정산

![image](https://github.com/SawSimE/SolTrip/assets/66519915/4df85848-0952-4b07-b01b-b29a6ce23d7d)
![image](https://github.com/SawSimE/SolTrip/assets/66519915/f716b467-f74b-420c-9daf-d0e36f8bcd09)
<img src="https://github.com/gayong/SolTrip/assets/122499571/aa901468-0487-4308-9152-082442203a3e" width="325"/>

- 정산이 필요한 내역을 체크하여 이미지 저장 형태로 다른 사람에게 공유

<br/>

### 7. 포트폴리오

7.1 포트폴리오 메인

<img src="https://github.com/gayong/SolTrip/assets/122499571/2a0b454a-4e11-4c28-946c-2a30056bbbc7" width="325"/>
<img src="https://github.com/gayong/SolTrip/assets/122499571/21fbea31-2eee-4f4d-aef9-0d41767302dd" width="325"/>

(좌) 끝마친 여행이 없을 때 / (우) 끝마친 여행이 있을 때

7.2 포트폴리오

<img src="https://github.com/gayong/SolTrip/assets/122499571/f2e451c2-5a5e-4bf6-99af-86edfeb4bbec" width="325"/>

- 여행을 마친 후, 위치별 결제 내역과 그에 따른 이동 경로 순서대로 지도에 표시

<br/>

## 👥 팀원 소개
<a name="item-six"></a>

| **Name**     | 심규렬                                                                  | 김성인                                                                  | 공정민                                                                  | 이가영                                                                  |
|:------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| **Profile**  | <img src="https://github.com/SawSimE/SolTrip/assets/66519915/1f0fd1e1-2877-41cb-8e9f-479f17775985" width="135" height="155"/>| <img src="https://github.com/SawSimE/SolTrip/assets/66519915/a97e3428-4818-4613-81fd-ec1904e50e23" width="145" height="155"/> |  <img src="https://github.com/SawSimE/SolTrip/assets/66519915/b1b2ac31-0453-49dd-8a1c-ca378b229cab" width="145" height="155"/> | <img src="https://github.com/SawSimE/SolTrip/assets/66519915/aae41061-bf70-4cb8-9ef0-60e993579419" width="145" height="150"/>  |
| **Position** |  Backend                                             | Backend                                                              | Frontend                                                             | Frontend                                                                                                                     |
| **Position** | Server 구축 <br/> 인기장소 조회 API <br/> 여행 계획 API          | 유저 관리 API <br/> 예산 사용 내역 API <br> 포트폴리오 API                                     | 여행 계획 <br/> 예산 설정  <br/> UX/UI                          | 로그인/잔액조회 <br/> 예산 분석/거래내역 <br/>  정산하기/포트폴리오     |
| **Git**      | [GitHub](https://github.com/simgyuryeol)                             | [GitHub](https://github.com/ksi2564)                              | [GitHub](https://github.com/gayong)                              | [GitHub](https://github.com/jeongmin59)|

<br/>
