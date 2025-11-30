# 📌 Employee Attendance Management System (MERN)

A complete MERN stack attendance management system with authentication, employee dashboard, admin dashboard, check-in/check-out, attendance summary, CSV export, and date-range filtering.

---

## 🚀 Features

### 👤 Employee Features
- Check-In / Check-Out
- Today’s Attendance Status
- Monthly Summary
- Total Hours Worked
- Last 7 Days Attendance
- Employee Dashboard with charts

### 👨‍💼 Admin / Manager Features
- View All Employees Attendance
- View Single Employee Attendance
- Team Summary & Attendance Breakdown
- Date Range Filter (From → To)
- Export Attendance as CSV
- Admin Dashboard with analytics

---

## 🛠️ Tech Stack

### Frontend
- React (Vite)
- Axios
- Redux Toolkit
- Custom CSS

### Backend
- Node.js  
- Express.js  
- MongoDB (Mongoose)  
- JSON Web Tokens  
- bcrypt.js  

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/CHEEDELLAYOSHITHA/Employee-Attendance-System.git
cd Employee-Attendance-System
```

---

## 2️⃣ Backend Setup
```bash
cd backend
npm install
```

Create `.env` file inside backend:

```
MONGO_URI=mongodb://127.0.0.1:27017/attendance
JWT_SECRET=your_jwt_secret_key
PORT=5000
```

Start backend:
```bash
npm start
```

---

## 3️⃣ Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

---

## 🌍 Environment Variables

Your `.env.example` file:

```
MONGO_URI=mongodb+srv://nuwanisitharacom:nuwani808@cluster0.njcwh4b.mongodb.net/system_db?retryWrites=true&w=majority&appName=Cluster0
JWT_SECRET=supersecretkey
PORT=5000
```

Place this file inside **backend/** so anyone can set up the project easily.

---

## 📂 Folder Structure

```
Employee-Attendance-System/
│── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   ├── .env.example
│
│── frontend/
│   ├── src/
│   │   ├── pages/
│   │   ├── components/
│   │   ├── redux/
│   │   └── App.jsx
│
└── README.md
```

---

## 🎯 Future Scope
- QR Code Check-In system  
- Face Recognition Attendance  
- Leave & Holiday Management  
- Push Notifications  
- Employee Device Tracking  

---

## 👩‍💻 Developed By
**Yoshitha**  
MERN Stack Developer  

