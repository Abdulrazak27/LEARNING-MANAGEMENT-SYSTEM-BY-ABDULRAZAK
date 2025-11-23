<img width="1919" height="1079" alt="lms-sql1" src="https://github.com/user-attachments/assets/3c6461ec-b860-4c42-bf46-251bbee0c668" />🌟 Learning Management System (LMS)

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

screenshots of project:
<img width="1919" height="1079" alt="lms-sql1" src="https://github.com/user-attachments/assets/87ae4f3a-4a36-4012-934e-ad149b440f8b" />
<img width="1919" height="1079" alt="lms-sql-2" src="https://github.com/user-attachments/assets/bfef3ff8-2b45-47a0-8022-6bdb7723f07c" />
<img width="1919" height="1079" alt="lms-sql3" src="https://github.com/user-attachments/assets/961790a8-b494-442c-87ff-d389ce2b15c4" />
<img width="1919" height="1030" alt="lms-sql4" src="https://github.com/user-attachments/assets/28434fac-b058-47ca-8e0d-04c15105f19b" />
<img width="1919" height="854" alt="lms-sql-5" src="https://github.com/user-attachments/assets/2e636167-aa2f-4c47-92a6-383b402eb717" />
<img width="1412" height="946" alt="lms-sql-7" src="https://github.com/user-attachments/assets/a7f1d59f-0182-4d0a-8491-90389e1c4da8" />
<img width="1864" height="1079" alt="lms-sql-8" src="https://github.com/user-attachments/assets/68933b04-48c8-415b-b6da-971c7cbc54aa" />







