### Result Management System

# Project Overview
The **Result Management System** is a web-based application designed to help teachers manage student records and allow students to view their results securely. The project ensures **secure authentication**, **role-based access**, and a **user-friendly interface**.

# Features
- **Teacher Dashboard** – Manage student records (Add, Edit, Delete Results).
- **Student Portal** – View results using **Roll Number & DOB**.
- **Authentication** – Secure login for teachers and students.
- **Error Handling** – Prevent unauthorized access.
- **Responsive UI** – Built with **EJS** and **Bootstrap**.

# Tech Stack
#### Frontend:
- EJS (Embedded JavaScript)
- Bootstrap
- JavaScript, HTML, CSS

### Backend:
- Node.js, Express.js
- MongoDB (Mongoose ORM)
- Session-based Authentication

# Deployment:
- **Backend** – Local Server / Render / AWS EC2
- **Database** – MongoDB Atlas / Local MongoDB

# Installation & Setup
1️⃣ Clone the Repository:
```
git clone https://github.com/yourusername/Result-Management-System.git
cd Result-Management-System
```

2️⃣ Backend Setup:
```
cd backend
npm install
```
Create a **.env** file and add:
```
MONGO_URI=your_mongodb_uri
SESSION_SECRET=your_session_secret
```
Run the backend:
```
npm start
```

 # API Endpoints
| Method | Endpoint | Description |
|--------|---------|-------------|
| POST | /auth/login | Login for Teachers & Students |
| GET | /students/:rollNumber | Fetch Student Result |
| POST | /students | Add Student Result (Teacher Only) |

# Future Enhancements
- Migrate frontend to React for better performance
- Implement JWT authentication for better security
- Optimize MongoDB queries for faster response

# Contributing
Feel free to fork the repo and submit pull requests. Suggestions are welcome!

# License
MIT License. Free to use and modify.

---
🚀 Developed by Neeraj Yadav
