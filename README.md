# Online Quiz Portal

>[!TIP]
>Online-Quiz-Portal App은 온라인으로 퀴즈를 생성하고 참가할 수 있는 웹 애플리케이션입니다. 사용자는 퀴즈를 풀고, 결과를 확인하며, 다른 사용자가 만든 퀴즈에 참여할 수 있습니다. 관리자는 퀴즈를 만들고, 참가자를 관리하며, 통계를 볼 수 있는 기능도 제공합니다.

## 주요 기능:
### 1.👤 사용자 관리
- 사용자는 회원가입 후 로그인하여 퀴즈에 참여하거나, 자신이 만든 퀴즈를 관리할 수 있습니다.
- 프로필 수정 및 비밀번호 변경 기능을 제공합니다.

### 2.📝 퀴즈 생성
- 관리자는 다양한 유형의 질문을 포함하는 퀴즈를 생성할 수 있습니다 (예: 객관식, 주관식 등).

### 3.❓ 퀴즈 참가
- 사용자들은 생성된 퀴즈에 참여하여 질문에 답할 수 있습니다.
- 퀴즈 완료 후 즉시 결과를 확인할 수 있습니다.

### 4.🕒 실시간 점수
- 퀴즈 참가자가 답안을 제출하면 즉시 점수를 확인할 수 있습니다.
- 참가자는 퀴즈 종료 후 자신의 점수를 보고 분석할 수 있습니다.

### 5.📊 퀴즈 결과
- 참가자는 퀴즈 결과를 점수와 함께 확인하고, 틀린 문제를 다시 리뷰할 수 있습니다.
- 관리자 및 사용자는 전체 퀴즈 통계를 볼 수 있습니다.

### 5.🔍 퀴즈 목록 및 검색
- 사용자는 다양한 퀴즈 목록을 보고, 관심 있는 주제나 난이도의 퀴즈를 선택하여 참여할 수 있습니다.
- 검색 기능을 통해 특정 퀴즈나 주제를 찾을 수 있습니다.

### 6.🛠️ 관리자 대시보드
- 관리자에게 퀴즈 통계, 참가자 목록, 퀴즈 수정 및 삭제 기능을 제공.
- 퀴즈의 인기 정도나 사용자 참여를 관리하고 분석할 수 있습니다.

### 7.⏱️ 퀴즈 타이머
- 퀴즈 시작과 종료 시간을 설정하여 제한 시간 내에 퀴즈를 완료하도록 유도합니다.

### 8.💾 데이터 저장
- 사용자의 점수와 퀴즈 결과를 저장하여 나중에 확인할 수 있도록 합니다.

## 주요 기술 스택
### Front-End: [ React,React Redux/Toolkit, React-Router-DOM,Antd Design, Axios etc]
>[!NOTE]
>###  ⚛️ React:
>- React (^18.2.0)를 사용하여 사용자 인터페이스를 구축하고 애플리케이션 상태를 관리합니다.
>- ReactDOM (^18.2.0)을 사용하여 React 컴포넌트를 DOM에 렌더링합니다.
>### 🔄 Redux & Redux Toolkit
>- Redux (^4.2.0)를 사용하여 전역 상태를 관리합니다.
>- Redux Toolkit (^1.8.5)을 사용하여 Redux 개발을 간소화하고, 스토어 설정, 리듀서 및 액션을 효율적으로 처리합니다.
>### 🌐 React Router
>- React Router DOM (^6.4.1)을 사용하여 애플리케이션 내에서 페이지와 뷰 간의 라우팅 및 네비게이션을 처리합니다.
>### 💻 Ant Design
>- Ant Design (^4.23.4)을 사용하여 일관된 디자인 시스템을 제공하며, 폼, 테이블, 버튼 등 다양한 UI 컴포넌트를 구현합니다.
>### 🌍 Axios
>- Axios (^0.27.2)를 사용하여 백엔드 API 호출을 처리하고, 데이터 페칭을 원활하게 수행합니다.
>### 📅 Moment.js
>- Moment.js (^2.29.4)를 사용하여 날짜와 시간을 읽기 쉬운 형식으로 파싱하고 조작합니다.

### Back-End: [ Node.js, Express.js, Bycript.js, JsonWebToken, Mongoose etc.]
>[!NOTE]
>### 🔐 bcryptjs
>- bcryptjs (^2.4.3)를 사용하여 비밀번호 해싱을 수행, 사용자 자격 증명이 안전하게 데이터베이스에 저장되고 보호되도록 처리합니다.
>### 🌿 dotenv
>- dotenv (^16.0.3)를 사용하여 .env 파일에서 환경 변수를 로드하고, API 키, 데이터베이스 자격 증명, 앱 설정과 같은 민감한 정보를 안전하게 관리합니다.
>### 🚀 Express
>- Express (^4.18.1)를 사용하여 서버를 설정, HTTP 요청 처리, 라우팅 및 미들웨어를 빠르고 간단하게 처리할 수 있게 합니다.
>### 🔑 jsonwebtoken
>- jsonwebtoken (^8.5.1)를 통합하여 **JWT (JSON 웹 토큰)**을 생성하고 검증, 사용자 인증 및 권한 부여를 안전하게 수행합니다.
>### 💾 mongoose
>- mongoose (^6.6.4)를 사용하여 MongoDB 객체 모델링을 진행, MongoDB 데이터베이스와 상호작용하고, 스키마 정의 및 CRUD 작업을 손쉽게 처리할 수 있게 합니다.
>###🔄 nodemon
>- nodemon (^2.0.20)을 설정하여 개발 중 서버 코드가 변경될 때 자동으로 서버를 재시작, 실시간으로 업데이트가 가능합니다.



## 프로젝트를 통해 얻은 성과와 배운 점들은 다음과 같습니다:
### 1.🕒 실시간 기능 구현 (Real-Time Features)
- 사용자들이 실시간으로 퀴즈 질문을 받고 답을 제출하며, 결과를 즉시 확인할 수 있도록 실시간 통신을 처리하는 방법을 배울 수 있었습니다.
- 답안 제출 상태 업데이트, 실시간 점수 보드 등을 구현하면서 비동기 처리와 실시간 데이터 흐름에 대한 이해를 깊게 할 수 있었습니다.

### 2.🔐 사용자 인증 및 세션 관리
- 퀴즈 플랫폼에서 로그인, 회원가입, 사용자 인증을 처리하는 기능을 구현하면서 JWT (JSON Web Tokens)를 사용한 인증 시스템을 다시 한번 경험해 봤습니다. 또한, 세션 관리를 통해 사용자 맞춤형 경험을 제공하는 방법을 배웠습니다.

### 3.🌐 RESTful API 설계 및 데이터 처리
- RESTful API를 사용하여 퀴즈에 필요한 다양한 엔드포인트를 설계하고 구현하는 경험을 얻었고 실력을 높혔습니다. 예를 들어, 사용자 등록, 퀴즈 질문 목록 가져오기, 퀴즈 제출, 점수 기록 등의 기능을 API로 구현하면서 HTTP 메소드(GET, POST, PUT, DELETE)와 상태 코드를 이해하고 적절하게 활용하는 법을 다시 한접 실습하면서 지식을 상항시켰습니다.

### 4. 📂 실시간 데이터베이스 관리
- MongoDB를 사용하여 실시간으로 퀴즈 질문과 결과를 저장하고, 동시성을 처리하는 방법을 배우는데 좋은 경험 되었습니다.비정형 데이터를 처리하고, 데이터베이스 설계,스키마 설계 및 쿼리 최적화 기술을 더 많이 익숙하는데 도움 되었습니다.

### 5.🔗 프론트엔드와 백엔드 통합
- React를 사용한 클라이언트 사이드와 Node.js/Express.js를 사용한 서버 사이드의 통합 경험을 쌓을 수 있었습니다. 퀴즈 응답을 서버로 전송하고, 실시간으로 결과를 반영하는 인터페이스를 구현하는 것이 클라이언트-서버 상호작용을 이해하는데 큰 더움 되었습니다.

### 6. 📊 상태 관리
- Redux 활용하여 퀴즈 진행 상태(예: 현재 문제, 점수 등)를 애플리케이션 상태로 관리하는 방법을 배울 수 있었습니다. 사용자 인터페이스의 상태를 일관되게 유지하고, 다양한 컴포넌트 간의 상태 공유를 효율적으로 처리하는 방법을 익혀 봤습니다.

### 7.🎨 UI/UX 디자인
- Ant Design UI 라이브러리를 사용하여 퀴즈 인터페이스를 구축하면서 사용자 경험을 개선하도록 해 봤습니다.이를 통해 어떻게 외부 UI 라이브러리가 나의 프로젝트 적용하는 것을 배웠고  UI 디자인하는데 큰 시간을 절약할 있는지 깨달았습니다.

## Problems & Challanges
| Error & Problem Title | Status | Difficult | Date |
|--|--|--|--|
|[🎨 TailwindCSS Conflicts](https://github.com/BekCodingAddict/FastPizza/blob/master/Problems/TailwindCSS-Conflicts.md) | ![solved](https://img.shields.io/badge/solved-blue) | low | Oct 3, 2024 |

## UI/UX
Login:
<img width="1275" height="945" alt="QuizPortal" src="https://github.com/user-attachments/assets/e70e371b-8735-4afd-8e6a-898c5de03f61" />

Home:
<img width="1271" height="942" alt="QuizPortal-Home" src="https://github.com/user-attachments/assets/9d2cd4cf-9843-40d4-83b8-298e710b3079" />

Quiz List:
<img width="1277" height="954" alt="QuizPortal-Quiz" src="https://github.com/user-attachments/assets/a37f203a-f38d-45c1-b14e-0665dac449d3" />

Report:
<img width="1329" height="958" alt="QuizPortal-Report" src="https://github.com/user-attachments/assets/90abb2dd-a0ac-4b1a-ab9b-fc4c9f14f4c0" />

Quiz Result:
<img width="1330" height="958" alt="QuizPortal-Result" src="https://github.com/user-attachments/assets/f45807b8-b66f-4e33-a9dd-a9239c6a2184" />

Testing:
<img width="1279" height="957" alt="QuizPortal-Testing" src="https://github.com/user-attachments/assets/e397a8c2-e5a1-45e4-9996-aa4a970d2986" />




### 결론
이 프로젝트를 통해 실시간 웹 애플리케이션의 전반적인 개발 프로세스를 이해하고, 프론트엔드와 백엔드를 연계하여 동적인 애플리케이션을 구축하는 기술을 습득할 수 있었습니다. 실시간 데이터 처리, 사용자 인증 및 보안, UI/UX 설계 등 다양한 분야에서 경험을 쌓고 실력을 향상시킬 수 있었습니다.🚀


## 앞으로 추가 해야 할 기능들 정리
- [ ] 퀴즈 카테고리 및 난이도 설정 (Categories & Difficulty Levels):
  - 퀴즈는 다양한 카테고리와 난이도(쉬움, 보통, 어려움)로 나누어져 있으며, 참가자는 원하는 카테고리와 난이도를 선택하여 참여할 수 있습니다.
- [ ] 관리자 대시보드 (Admin Dashboard) 더 현대적으로 압데이트하기 

