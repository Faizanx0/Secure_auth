# 🔐 SecureAuth

A production-ready Full Stack Authentication System built using **Node.js, Express.js, MongoDB Atlas, JWT, and Vanilla JavaScript.**

SecureAuth provides a reusable authentication module for developers building web applications, hackathon projects, or MVPs. Instead of rebuilding authentication from scratch, simply clone, configure, and customize.

---


# 🌐 Live Demo

### Frontend

https://secure-auth-git-main-abhinav-dixits-projects-9016b694.vercel.app

### Backend

https://secure-auth-357h.onrender.com

---

# ✨ Features

## Authentication

- ✅ User Signup
- ✅ Secure Login
- ✅ JWT Authentication
- ✅ Logout
- ✅ Protected Dashboard

## Email Verification

- ✅ Email OTP Verification
- ✅ OTP Expiry
- ✅ Resend OTP

## Password Recovery

- ✅ Forgot Password
- ✅ OTP Verification
- ✅ Reset Password

## Security

- ✅ bcrypt Password Hashing
- ✅ JWT Token Authentication
- ✅ Protected Routes
- ✅ MongoDB Atlas Integration

## User Experience

- ✅ Password Visibility Toggle
- ✅ Toast Notifications
- ✅ Responsive Design
- ✅ Dashboard
- ✅ Client-side Validation

---

# 🛠 Tech Stack

## Frontend

- HTML5
- CSS3
- Vanilla JavaScript

## Backend

- Node.js
- Express.js

## Database

- MongoDB Atlas
- Mongoose

## Authentication

- JWT
- bcrypt

## Email Service

- Nodemailer

## Deployment

- Vercel
- Render

---

# 📂 Project Structure

```text
SecureAuth/

│

├── client/
│   ├── assets/
│   ├── css/
│   ├── js/
│   └── pages/
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── utils/
│   ├── .env.example
│   ├── package.json
│   └── server.js
│
├── screenshots/
│
├── LICENSE
├── README.md
└── .gitignore
```

---

# 🚀 Installation

Follow these steps to set up SecureAuth locally.

### 1. Clone the repository

```bash
git clone https://github.com/Abhinavjs903/Secure_auth.git
```

### 2. Open the project directory

```bash
cd Secure_auth
```

### 3. Go to the server directory

```bash
cd server
```

### 4. Install server dependencies

```bash
npm install
```

### 5. Configure environment variables

Create a `.env` file inside the `server` directory using `.env.example` as a reference.

Add the required values for:

* `PORT`
* `MONGO_URI`
* `JWT_SECRET`
* `EMAIL_USER`
* `EMAIL_PASS`

Keep your actual credentials and secrets private. Do not commit your `.env` file to GitHub.

### 6. Start the backend server

```bash
npm run dev
```

### 7. Open the frontend

Open the frontend files from the `client` directory using a local development server such as Live Server, or deploy the frontend to Vercel.


# 📸 Screenshots

## Login

![Login](screenshots/Screenshot 2026-08-06 111405.jpg)

## Signup

![Signup](screenshots/Screenshot 2026-08-06 111435.jpg)

## Forgot Password

![Forgot Password](screenshots/Screenshot 2026-08-06 111446.jpg)

## Dashboard

(Add Screenshot)

---

# 🎯 Learning Objectives

This project demonstrates:

- REST APIs
- MVC Architecture
- JWT Authentication
- Password Hashing
- Email OTP Verification
- MongoDB Integration
- Secure Authentication Flow
- Production Deployment
- Modular JavaScript
- Full Stack Development

---

# 🤝 Contributing

Contributions, issues, and feature requests are welcome.

Feel free to fork the repository and improve SecureAuth.

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Author

**Abhinav Dixit**

If this project helped you, consider giving it a ⭐ on GitHub.
