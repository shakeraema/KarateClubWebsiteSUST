# 🥋 SUST Karate Club – Web Management System

A full-stack web application to digitize the operations of the Karate Club at Shahjalal University of Science and Technology (SUST). The system allows students to register, pay fees, track belt progress, and stay updated on events, while instructors can manage students, send notifications, and maintain schedules.

---

## 🚀 Features

### 👤 Student Module
- Online registration with image upload
- Secure login & profile management
- SSLCommerz-based payment processing
- Belt progression tracking & certificate uploads
- Class & exam routines
- Personalized notifications

### 👨‍🏫 Instructor/Admin Module
- Secure login & editable profile
- Manage student belts and certificates
- Send role-based notifications (belt, payment, announcements)
- Post announcements and upcoming exams
- Edit club information (About Us, Mission, Vision)

### 🌐 Public Features
- Home, About, Gallery, and Upcoming Events pages
- Instructor list & Join Us functionality

---

## 🧑‍💻 Tech Stack

| Layer         | Technology                           |
|---------------|--------------------------------------|
| Frontend      | React + Vite + Tailwind CSS          |
| Backend       | Node.js + Express.js                 |
| Database      | MySQL                                |
| File Uploads  | Multer + Cloudinary                  |
| Payments      | SSLCommerz                           |
| Auth & Security | Bcrypt, Role-based routing         |

---

## 🗃️ Project Structure

frontend/
├── src/
│ ├── components/ # UI components
│ ├── pages/ # React pages (routes)
│ ├── context/ # App-level context provider
│ ├── App.jsx # Main route config
│ └── main.jsx # Entry point
├── index.html
├── tailwind.config.js
└── vite.config.js

backend/
├── config/ # DB and cloudinary config
├── middlewares/ # Multer file handler
├── server.js # Express app
└── SUST_Karate_Club.sql # Database schema


---

## ⚙️ Installation

### 1️⃣ Backend Setup

{```bash
cd backend
npm install
npm run server
}


## Create a .env file:
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=your_password
DB_NAME=SUST_Karate_Club

CLOUDINARY_CLOUD_NAME=xxx
CLOUDINARY_API_KEY=xxx
CLOUDINARY_API_SECRET=xxx

2️⃣ Frontend Setup
bash
Copy
Edit
cd frontend
npm install
npm run dev

Frontend will run at: http://localhost:5173
Backend runs at: http://localhost:4000

📦 Environment Variables
Set the following in both frontend and backend:

env
Copy
Edit
# Cloudinary
CLOUDINARY_CLOUD_NAME=
CLOUDINARY_API_KEY=
CLOUDINARY_API_SECRET=

# MySQL
DB_HOST=
DB_USER=
DB_PASSWORD=
DB_NAME=
🔐 Roles & Access
Student

View/update profile

Pay fees

Track belts, get notifications

Instructor

Manage students

Upload certificates

Send notifications

Post exam schedules

Public

Access events, instructors, and registration

📸 Screenshots

📣 Contributions
Contributions 

🪪 License
SUST © 2025 [Shakera-Nivrita / SUST]
