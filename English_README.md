# Online-Quiz-Portal
>[!TIP]
>The Online Quiz Portal is a full-stack web application built with the MERN stack (MongoDB, Express.js, React, and Node.js). It provides users and admins with a platform to create, participate in, and manage quizzes efficiently.

## Key Features:
### 👤 User Management
- Users can sign up, log in, and manage their profile.
- Features include editing profiles and changing passwords.
### 📝 Quiz Creation
- Admins can create quizzes with various question types (e.g., multiple choice, short answers).
### ❓ Quiz Participation
- Users can join quizzes, answer questions, and get instant results after completion.
### 🕒 Real-time Scoring
- Scores are calculated immediately upon answer submission.
- Users can analyze their scores after the quiz ends.
### 📊 Quiz Results
- Participants can review their scores and revisit incorrect answers.
- Admins and users can view overall quiz statistics.
### 🔍 Quiz List & Search
- Browse quizzes by topic or difficulty.
- Use search to find specific quizzes or subjects.
### 🛠️ Admin Dashboard
- Admins can view statistics, manage participants, and modify or delete quizzes.
- Analyze quiz popularity and user engagement.
### ⏱️ Quiz Timer
- Set start and end times for quizzes to enforce time limits.
### 💾 Data Storage
- Stores user scores and quiz results for future reference and analysis.
<hr/>

## Achievements and Lessons Learned from the Project
### 1. 🕒 Real-Time Features
- Implemented real-time communication for users to take quizzes and see results instantly.
- Gained experience in asynchronous handling and real-time data flow, including live updates and scoreboards.
### 2. 🔐 User Authentication and Session Management
- Developed a JWT-based authentication system for login and registration.
- Learned how to manage sessions to offer personalized experiences to users.
### 3. 🌐 RESTful API Design and Data Handling
- Designed and implemented RESTful APIs using HTTP methods (GET, POST, PUT, DELETE) for various features like user registration and score recording.
- Strengthened API design and data handling skills.
### 4. 📂 Real-Time Database Management
- Used MongoDB for storing quiz questions and results, learning how to manage data concurrency.
- Gained skills in database design, schema development, and query optimization.
### 5. 🔗 Frontend-Backend Integration
- Integrated React for the frontend with Node.js/Express.js for the backend.
- Improved understanding of client-server interaction by reflecting quiz results in real-time.
### 6. 📊 State Management
- Used Redux to manage quiz progress (e.g., current question, score).
- Efficiently handled shared state across components, ensuring consistent UI.

## Problems & Challanges
| Error & Problem Title | Status | Difficult | Date |
|--|--|--|--|
|[🎨 TailwindCSS Conflicts](https://github.com/BekCodingAddict/FastPizza/blob/master/Problems/TailwindCSS-Conflicts.md) | ![solved](https://img.shields.io/badge/solved-blue) | low | Oct 3, 2024 |

## UI Screenshots

## Conclusion
This project provided a comprehensive experience in real-time web application development, covering both frontend and backend integration.

- Key Technologies: Real-time data handling, user authentication, RESTful API, state management, and UI/UX design.
- The project enhanced my practical skills in building dynamic applications with real-time features. 🚀


 ## How to Install?
   - For BackEnd dependencies:
```
npm install
```
  - For FrontEnd dependencies:
```
cd client && npm install
```
  - After FrontEnd and BackEnd dependencies Installation turn on Nodemon server.
  - In the root:
```
nodemon server.js
```
  - Next:
```
cd client && npm start
```
  - Access the web app at http://localhost:3000/
  

