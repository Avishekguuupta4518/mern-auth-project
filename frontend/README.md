# 🔐 Advanced MERN Authentication System

A complete **secure authentication system** built using the **MERN Stack** with modern features like:

- JWT Access & Refresh Tokens  
- Email Verification with OTP  
- Forgot Password & Reset Password  
- Change Password  
- Google Login Integration  
- Secure Password Hashing using bcrypt  
- Protected Routes & Middleware  

This project is designed to be production-ready and scalable for real-world applications.

---

## 🚀 Features

✅ User Registration with Validation  
✅ Email Verification using OTP  
✅ Secure Login with JWT Authentication  
✅ Access Token + Refresh Token Flow  
✅ Forgot Password with Email OTP  
✅ Reset Password Functionality  
✅ Change Password Securely  
✅ Google Login Integration  
✅ Authentication Middleware  
✅ Fully Responsive Frontend UI  

---

## 🛠 Tech Stack

### Frontend
- React.js  
- React Router DOM  
- Axios  
- Tailwind CSS (if used)

### Backend
- Node.js  
- Express.js  
- MongoDB + Mongoose  

### Authentication & Security
- JWT (JSON Web Token)  
- bcrypt.js (Password Hashing)  
- Nodemailer (Email OTP Sending)  

---

## 📂 Project Structure

MERN-Auth-Project/
│
├── backend/
│   ├── config/
│   ├── controllers/
│   ├── database/
│   ├── emailverify/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── validators/
│   └── server.js
│
├── frontend/
│ ├── src/
│ ├── components/
│ ├── pages/
│ ├── App.jsx
│ └── main.jsx
│
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/mern-auth-system.git
cd mern-auth-system
2️⃣ Backend Setup
Go to backend folder:

bash
Copy code
cd backend
npm install
Create a .env file inside backend/:

env
Copy code
PORT=5000
MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret_key
JWT_REFRESH_SECRET=your_refresh_secret_key

EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_app_password

CLIENT_URL=http://localhost:5173
Run backend server:

bash
Copy code
npm start
Backend will run at:

arduino
Copy code
http://localhost:5000
3️⃣ Frontend Setup
Go to frontend folder:

bash
Copy code
cd ../frontend
npm install
Run frontend:

bash
Copy code
npm run dev
Frontend will run at:

arduino
Copy code
http://localhost:5173
🔑 Authentication Flow
User Registration
User signs up with email + password

OTP is sent to email

Account activates after verification

Login
User logs in

Access + Refresh tokens are generated

Forgot Password
OTP sent to registered email

Password reset after verification

Change Password
Logged-in user can securely update password

🔒 Security Highlights
Passwords hashed using bcrypt

JWT-based authentication middleware

Refresh token support for long sessions

OTP-based email verification

Protected API routes

📸 Screenshots (Optional)
Add screenshots here:

md
Copy code
![Login Page](screenshots/login.png)
![OTP Verification](screenshots/otp.png)
🌐 Future Improvements
Role-based authentication (Admin/User)

Two-Factor Authentication (2FA)

Account Lock after multiple failed attempts

Deployment on Render/Vercel

🤝 Contribution
Contributions are welcome!

Fork this repository

Create a new branch

Make changes and commit

Submit a Pull Request

📜 License
This project is licensed under the MIT License.

👨‍💻 Author
Avishek Gupta
Computer Engineering Student
MERN Stack Developer

📧 Email: your-email@gmail.com
🌐 GitHub: https://github.com/your-username

⭐ If you found this project helpful, give it a star!

yaml
Copy code

---

# ✅ Next Level Upgrade (Tell me and I’ll do it)

If you want, I can instantly generate:

🚀 Professional GitHub README with badges  
📌 Deployment section (Vercel + Render)  
📷 Screenshot-ready template  
🧾 API Documentation (Postman style)  
🎯 Resume-ready Project Description  

Just paste your GitHub repo link or folder structure and I’ll tailor it exactly for your project.






