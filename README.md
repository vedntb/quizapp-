🎓 Online Quiz Application

Project ID: 65HIBKJS

-An interactive and secure Online Quiz Application built using Java, supporting user authentication, multiple quiz categories, MCQs, scoring, progress tracking, leaderboards, and a clean UI. Designed to automate quiz-taking and enhance learning efficiency.

📌 Project Description

-The Online Quiz Application enables users to register, log in, take quizzes on different topics, view results instantly, and track their performance over time. Administrators can create and manage quizzes, questions, and scores through a dedicated quiz management panel.

🚀 Features
👤 User Authentication

-Secure user registration & login

-Password hashing + salting for security

-Validation and error handling

📝 Quiz Management (Admin Panel)

-Create quizzes on various topics

-Add, edit, delete multiple-choice questions

-Supports four options per question

-Store correct answers in the database

-CRUD operations implemented using JDBC

🧠 Quiz Taking (Users)

-Select from available quizzes

-One question shown at a time

-Choose an option and submit

-Immediate feedback: Correct/Incorrect

-Timer-based questions (optional)

-Random question selection (optional)

📊 Scoring & Progress Tracking

-Score displayed at end of quiz

-Track all quiz attempts

-Users can view past scores and attempts

-Attempt history stored in database

🏆 Leaderboard (Optional)

-Top performers ranked by:

-total score

-average score

-Leaderboard displayed per quiz / overall

🎨 User Interface

-Built using Java Swing / JavaFX

-Clean, intuitive, user-friendly layout

-Smooth navigation between screens

💾 Data Persistence

-Database support: MySQL / SQLite

-JDBC-based CRUD operations

-Tables include:

-users

-quizzes

-questions

-quiz_attempts

-leaderboard (optional)

🛡️ Security Considerations

-Password hashing + salting

-Input validation

-SQL injection prevention

-Exception handling

📚 Documentation

-Setup guide

-Project structure

-Code documentation (comments)

-Assumptions & limitations

📂 Project Structure

OnlineQuizApplication/
│
├── src/
│   ├── auth/
│   │   ├── Login.java
│   │   └── Register.java
│   ├── admin/
│   │   ├── QuizManager.java
│   │   └── QuestionEditor.java
│   ├── quiz/
│   │   ├── QuizList.java
│   │   ├── QuizWindow.java
│   │   └── ScoreSummary.java
│   ├── database/
│   │   ├── DBConnection.java
│   │   └── CRUDOperations.java
│   ├── models/
│   ├── Leaderboard.java
│   └── Utils.java
│
├── assets/
│   ├── icons/
│   └── sounds/
│
├── docs/
│   ├── user_manual.pdf
│   └── setup_guide.md
│
└── README.md

🛠️ Technologies Used

-Java (JDK 8+)

-Java Swing / JavaFX

-MySQL / SQLite

-JDBC

-OOP Principles

-Exception handling & validation

⚙️ How to Run

1️⃣ Clone the Repository
git clone https://github.com/your-username/online-quiz-application.git
cd online-quiz-application

2️⃣ Setup Database

Import provided SQL file

Update DB credentials in DBConnection.java

3️⃣ Compile the Project
javac src/**/*.java

4️⃣ Run the Application
java Login

📌 Future Enhancements

-Difficulty levels (easy/medium/hard)

-Advanced analytics for users

-Email-based password reset

-Export score reports (PDF/CSV)

-UI themes (dark/light/custom)

-Mobile-friendly version

-Online multiplayer quizzes

## 👨‍💻 Author 
**Vedant Bhonde** 

📧 vedantbhonde01@gmail.com
🔗 [GitHub Profile] ([https://github.com/vedntb])
