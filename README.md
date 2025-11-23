A full-stack Learning Management System built with React (frontend), Spring Boot (backend), and MySQL (database).
This system supports course management, assessments, user progress tracking, certificates, discussions, and an admin panel.

🚀 Features
👤 User Management

Register & login

JWT-based authentication

User roles (Admin / Student)

Update profile information

📚 Course Management


Admin can add, edit, delete courses

Courses contain: title, description, instructor, image, etc.

Students can view and enroll in courses

📝 Assessments

Admin can add MCQs

Students can take assessments

Auto evaluation and score tracking

📈 Progress Tracking

Tracks user progress across enrolled courses

Visual representation of completion status

🏆 Certificate Generation

Auto-generated certificates after course completion

Includes student name + course title

💬 Discussion Forum

Course-specific discussion board

Students & instructors can interact

🛠 Admin Dashboard

Manage courses

Manage questions

View students, enrollments, and analytics

🧰 Technologies Used
🎨 Frontend

React

React Router

Tailwind CSS

Ant Design

Axios

React Player

jsPDF + html2canvas

Lucide Icons / FontAwesome

⚙️ Backend

Spring Boot

Java

Spring Security + JWT

Spring Data JPA

MySQL Driver

Maven

🗄 Database

MySQL

Main tables:
course, learning, user, progress, question, assessment, discussion, feedback

📁 Project Structure
Learning-Management-System-main/
│
├── backend/
│   ├── src/
│   ├── pom.xml
│   └── application-example.yml       (# Safe file for GitHub)
│
├── frontend/
│   ├── src/
│   ├── package.json
│
├── database/
│   └── lmsdatabase.sql               (# MySQL database dump)
│
└── README.md

🛠 Setup Instructions
1️⃣ Clone the Repository
git clone https://github.com/Abdulrazak27/LEARNING-MANAGEMENT-SYSTEM-BY-ABDULRAZAK.git
cd LEARNING-Management-System-main

🗄 Database Setup (MySQL)

Open MySQL / phpMyAdmin / Workbench

Create a database:

CREATE DATABASE lms;


Import the SQL file:

database/lmsdatabase.sql

🛡 Backend Setup (Spring Boot)

Go to backend folder:

cd backend


Copy the example config:

application-example.yml  →  application.yml


Add your own MySQL username and password inside the real application.yml.

Run the backend:

mvn spring-boot:run


Server runs at:

http://localhost:8080

🎨 Frontend Setup (React)

Go to frontend folder:

cd frontend


Install dependencies:

npm install


Start the frontend:

npm start


App will run at:

http://localhost:3000

💬 API Base URL

If needed, change it inside your React project:

http://localhost:8080/api

🧑‍💻 Author

Abdul Razak
Learning Management System — Full Stack Project

⭐ Contribute / Issues

If you'd like to improve this project or report bugs, feel free to open an issue or PR.

👍 License

This project is free to use for learning and improvement.






