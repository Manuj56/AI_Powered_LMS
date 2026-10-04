# 📚 AI-Powered LMS — The Future of Learning 🚀

An **AI-powered Learning Management System (LMS)** built using the **MERN Stack**, designed to make online learning smarter, simpler, and more interactive.

The platform provides a complete **EdTech experience** where students can discover courses using **Gemini AI-powered search**, securely sign in with **Google Authentication**, enroll in courses through **Razorpay**, and access personalized learning dashboards. Educators can create and manage courses, upload learning content, and manage their teaching dashboard.

The system also uses **Cloudinary and Multer** for efficient cloud-based media management, making it a scalable and user-friendly platform for modern online education.

### 🌐 Live Demo

👉 **[Try the AI-Powered LMS](https://ai-powered-lms-1-6aan.onrender.com/)**

---

## ✨ Key Features

- 🧠 **AI-Powered Smart Search** using Gemini AI
- 🔐 **Google Authentication** with Firebase
- 👨‍🎓 **Student & Educator Dashboards**
- 📚 **Course Creation & Management**
- 💳 **Razorpay Payment Gateway** for course enrollment
- ☁️ **Cloud Media Uploads** using Cloudinary & Multer
- ⚛️ **Redux Toolkit** for state management
- 📈 **Course Enrollment & Progress Tracking**
- 📱 **Fully Responsive UI** with React & Tailwind CSS

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| **Frontend** | React.js, Tailwind CSS, Redux Toolkit |
| **Backend** | Node.js, Express.js |
| **Database** | MongoDB, Mongoose |
| **Authentication** | Firebase Authentication, Google Sign-In |
| **Payments** | Razorpay |
| **AI** | Gemini AI API |
| **Cloud Storage** | Cloudinary, Multer |
| **Deployment** | Render, Vercel |
| **Database Hosting** | MongoDB Atlas |

---

## 🔄 How It Works

1. 🔐 User signs in using **Google Authentication**.
2. 👨‍🎓 User gets access based on their role — **Student or Educator**.
3. 👨‍🏫 Educators can create and manage courses and learning content.
4. 🧠 Students can discover courses using **Gemini AI-powered search**.
5. 💳 Students can enroll in courses through **Razorpay**.
6. 📚 Enrolled students can access lectures and track their learning progress.

---

## 📁 Project Structure

```text
AI-Powered-LMS/
│
├── client/                    # React Frontend
│   ├── src/
│   │   ├── components/        # Reusable UI Components
│   │   ├── pages/             # Application Pages
│   │   ├── redux/             # Redux Toolkit
│   │   ├── assets/            # Images & Static Assets
│   │   └── App.jsx            # Main Application
│   │
│   └── package.json
│
├── server/                    # Node.js + Express Backend
│   ├── controllers/           # Business Logic
│   ├── models/                # MongoDB/Mongoose Models
│   ├── routes/                # API Routes
│   ├── middleware/            # Authentication & Middleware
│   ├── config/                # Configuration
│   ├── uploads/               # Uploaded Media
│   ├── server.js              # Server Entry Point
│   └── package.json
│
├── .gitignore
├── README.md
└── package.json
