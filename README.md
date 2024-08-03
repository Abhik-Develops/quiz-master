# Quiz Master

An interactive quiz application for creating, managing, and participating in quizzes.

## Live Demo: https://quiz-master-8vww.onrender.com/

## Screenshots

![image](https://github.com/user-attachments/assets/6b9bc286-126b-4776-aa79-fdf9664c02b1)
![image](https://github.com/user-attachments/assets/d053bda8-853a-4d1e-ba71-934dfa9f50c9)
![image](https://github.com/user-attachments/assets/ad2f6efa-ef24-45ab-8ce1-612483242a27)
![image](https://github.com/user-attachments/assets/7c22a82a-35a2-4356-a4c1-d67e22677ff1)
![image](https://github.com/user-attachments/assets/9062cb56-b5f8-4c9f-8ffa-09f08242e504)
![image](https://github.com/user-attachments/assets/40755f44-b47a-4eba-a87f-aa4a2576b47f)
![image](https://github.com/user-attachments/assets/acb3c163-a0aa-4ef8-8946-57befc289c05)
![image](https://github.com/user-attachments/assets/8c8f7dff-af44-4cf2-b93d-c90b795d0786)
![image](https://github.com/user-attachments/assets/2cbe98f4-8e02-4d40-b3b2-8653fa740805)
![image](https://github.com/user-attachments/assets/3ac837e1-9c31-4bce-824a-33682194e5ad)
![image](https://github.com/user-attachments/assets/aebcc7b4-8ae8-4eff-9c12-ba51ad48f589)
![image](https://github.com/user-attachments/assets/ba38f3fa-2b33-421d-ad15-a5c23622233b)
![image](https://github.com/user-attachments/assets/c7e64b59-366f-41f6-b39c-6db2de4d0ee0)

![image](https://github.com/user-attachments/assets/855c18e1-bd9f-4b46-823a-5ef59b56f7fd)
![image](https://github.com/user-attachments/assets/d800306f-ff17-4400-9317-405abebb10e9)
![image](https://github.com/user-attachments/assets/67e56077-611f-4ffb-b159-f1a757d0426a)
![image](https://github.com/user-attachments/assets/cf56750a-673b-4d1c-a795-5113fe489cc5)
![image](https://github.com/user-attachments/assets/332d1bb9-bf6d-40dd-b155-c4776e3a8ac4)
![image](https://github.com/user-attachments/assets/e079011f-082a-4df6-be52-c9f489a98029)
![image](https://github.com/user-attachments/assets/b989f56a-cd55-490d-ae81-44de3c02960a)
![image](https://github.com/user-attachments/assets/83ff30c7-5e44-4a9f-8808-8d71bbbff261)
![image](https://github.com/user-attachments/assets/34964bde-9c58-44d3-a7e1-5c521854d6b7)
![image](https://github.com/user-attachments/assets/87e1d42b-6506-47a0-b089-dffea2ca4b7d)
![image](https://github.com/user-attachments/assets/9e5a2311-4c7e-4f09-af6a-c8a1d1ddc5bd)
![image](https://github.com/user-attachments/assets/4653e2fd-ce81-4f22-aeee-dd726c81c925)
![image](https://github.com/user-attachments/assets/4342ec37-eca8-4764-be2e-fc3cdb87692f)

## Overview

Quiz Master is a web-based platform that allows users to create, manage, and participate in quizzes. The application provides an interactive environment with various features such as user authentication, quiz creation, sharing, participation, feedback, and leaderboard functionalities.

## Features

- **User Authentication:** Secure user authentication with JWT.
- **Create Quizzes:** Users can create quizzes with multiple-choice questions.
- **Share and Join Quizzes:** Users can share quiz codes with others to join the quiz.
- **Lock/Unlock Quiz:** Authors can lock or unlock their quizzes. Locked quizzes cannot be attempted by others.
- **Feedback and Ratings:** Users can submit feedback and star ratings for quizzes they have attempted.
- **Review and Leaderboard:** Users can review questions and answers of attempted quizzes and view leaderboard results.
- **View Created Quizzes:** Users can view the questions and answers of the quizzes they have created.

## Technologies Used

- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js, MongoDB
- **Authentication:** JSON Web Tokens (JWT)

## Getting Started

### Prerequisites

- Node.js
- MongoDB

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Abhik-Develops/quiz-master.git
   cd quiz-master
   ```

2. Install dependencies for both frontend and backend:

   ```bash
   cd backend
   npm install
   cd ../frontend
   npm install
   ```

3. Set up environment variables:

   Create a `.env` file in the `backend` directory and add the following:

     ```env
    PORT=8000
    FRONTEND_URL="http://localhost:5173"
    VITE_BACKEND_URL="http://localhost:8000"
    DB_URL="your-mongodb-url"
    DB_NAME="fullstackdb"
    USER_NAME="your-database-username"
    USER_EMAIL="your-database-email"
    USER_PASS="your-database-password"
    JWT_SECRET="your-jwt-secret"
    NODE_ENV="development"


     ```

### Running the Application

1. Start the backend server:

   ```bash
   cd backend
   npm start
   ```

2. Start the frontend server:

   ```bash
   cd frontend
   npm run dev
   ```

3. Open your browser and navigate to `http://localhost:5173`

## Usage

- **Create a Quiz:** Log in and create a quiz by providing a title, questions, and multiple-choice options.
- **Share Quiz Code:** Share the generated quiz code with others to allow them to join the quiz.
- **Join a Quiz:** Enter the quiz code to join an existing quiz.
- **Submit Feedback:** After completing a quiz, submit feedback and rate the quiz.
- **Review Questions:** Review the questions and answers of attempted quizzes.
- **View Leaderboard:** See the leaderboard results for the quizzes.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.
