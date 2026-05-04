🎓 EduVerse Academy - Learning Management System

A full-stack Learning Management System built with React and Spring Boot, featuring course enrollment, progress tracking, assessments, and certificates.

## 🚀 Tech Stack

**Frontend**
- React.js
- Tailwind CSS
- Axios
- Ant Design
- React Router DOM

**Backend**
- Java Spring Boot
- Spring Security + JWT Authentication
- Hibernate / JPA
- MySQL

## ✨ Features

- 🔐 JWT-based Authentication (Register / Login / Logout)
- 👤 User Profile with Photo Upload
- 📚 Course Browsing with Search, Sort & Filter
- ✅ Course Enrollment System
- 🎥 Video-based Learning with Progress Tracking
- 📝 Assessments / Quizzes (unlocked at 100% progress)
- 🏆 Certificate Generation on Course Completion
- 💬 Discussion Forum per Course
- ⭐ Course Feedback System
- 🛡️ Role-based Access Control (USER / ADMIN / INSTRUCTOR)
- 📊 Performance Dashboard

## 🗂️ Project Structure
LEARNING-MANAGEMENT-SYSTEM/
├── backend/          # Spring Boot Application
│   ├── controller/
│   ├── service/
│   ├── entity/
│   ├── repository/
│   ├── security/
│   └── dto/
├── frontend/         # React Application
│   ├── src/
│   │   ├── api/
│   │   ├── pages/
│   │   ├── components/
│   │   └── contexts/
└── lmsdatabase.sql   # MySQL Database Dump

## ⚙️ Setup Instructions

### Prerequisites
- Java 17+
- Node.js 18+
- MySQL 8+
- Maven

### Database Setup
```sql
CREATE DATABASE lms;
USE lms;
-- Run lmsdatabase.sql
```

### Backend Setup
```bash
cd backend
# Update application.yml with your MySQL credentials
mvn spring-boot:run
```

### Frontend Setup
```bash
cd frontend
npm install
npm start
```

### Default Admin Credentials
Email: admin@gmail.com
Password: admin123

## 🌐 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/login | User Login |
| POST | /api/auth/register | User Register |
| GET | /api/courses | Get All Courses |
| GET | /api/learning/{userId} | Get Enrolled Courses |
| POST | /api/learning | Enroll in Course |
| GET | /api/progress/{userId}/{courseId} | Get Progress |
| POST | /api/assessments | Submit Assessment |
| GET | /api/certificates | Get Certificates |

## 👨‍💻 Developer

**Syed Abdul Razak**  
GitHub: [@Abdulrazak27](https://github.com/Abdulrazak27)

## 📄 License

This project is built for educational purposes.
