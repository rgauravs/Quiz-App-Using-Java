# Quiz-App-Using-Java
# 🎯 JavaFX Quiz Application

A full-featured desktop-based **Quiz Application** built using **JavaFX** and **SQLite**, featuring secure user login, admin controls, time-based quizzes, a feedback system, and result analysis.

---

## 📌 Features

### 👤 User Panel
- Secure login system
- Timed quiz questions
- Instant feedback after quiz submission
- Displays correct/incorrect answers at the end
- Result is stored and displayed with date/time

### 🔐 Admin Panel
- Secure admin login
- Add, update, and delete quiz questions
- View feedback submitted by users
- Manage question time limits individually
- Dashboard for monitoring quiz usage

### ⏱️ Quiz Features
- Each question has its own time limit
- Automatically moves to next question after time is up
- Scores are calculated and displayed at the end

### 💬 Feedback System
- Users can submit feedback after quiz
- Admin can view all feedback entries

---

## 🛠️ Technologies Used

| Tech | Description |
|------|-------------|
| JavaFX | GUI framework for building desktop apps |
| SQLite | Lightweight relational database |
| JDBC | Java Database Connectivity API |
| FXML | For structuring UI layout |
| Java 11+ | Compatible with Java 11 and above |


## 🚀 How to Run

### Prerequisites
- Java 11 or above installed
- JavaFX SDK configured
- SQLite JDBC driver added to the project
- IDE like IntelliJ IDEA or Eclipse

### Steps

1. Clone the repo:
```bash
git clone https://github.com/rgauravs/Quiz-App-Using-Java.git
```

2. Open in IDE and configure JavaFX and SQLite JDBC driver.

3. Run the Main.java file to start the application.

4. Use default credentials or manually insert users/admins into the database.

## ✨ Future Enhancements
Leaderboard support

Quiz categories (e.g., Science, History)

Export results as PDF

Password reset feature

Dark/light theme toggle

