# 🧊 Smart Fridge – Intelligent Food Inventory System

A **full-stack cloud-based web application** that helps users manage refrigerator inventory, track food expiry dates, and receive **automatic email reminders** before food items expire.

The system reduces food waste by notifying users when items are about to expire.

---

# 🚀 Live Backend API

Deployed on cloud:

https://smart-fridge-vdyg.onrender.com

---

# ✨ Key Features

### 🔐 Secure OTP Authentication

* Email-based login system
* One-time password verification for secure access

### 🧾 Smart Inventory Management

* Add food items with quantity and expiry date
* Delete items after usage
* User-specific fridge inventory

### ⏰ Automatic Expiry Reminders

* Background scheduler checks expiry dates
* Email alerts sent automatically before food expires
* No manual notification required

### ☁️ Cloud Deployment

* Backend hosted on Render
* Database hosted on MongoDB Atlas
* Accessible from anywhere

### 📧 Email Notification System

* Automated alerts using Nodemailer
* Reminds users to consume food before expiry

---

# 🛠️ Tech Stack

## Frontend

* HTML5
* CSS3
* JavaScript

## Backend

* Node.js
* Express.js

## Database

* MongoDB Atlas
* Mongoose ODM

## Email Service

* Nodemailer
* Gmail SMTP

## Deployment

* Render (Backend hosting)
* MongoDB Atlas (Cloud database)

---

# 🏗️ System Architecture

Frontend (HTML / JS)
⬇
Backend API (Node.js / Express)
⬇
MongoDB Atlas Cloud Database
⬇
Email Notification Service (Nodemailer)

---

# 📂 Project Structure

smart_fridge/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   ├── package.json
│   └── .env
│
├── frontend/
│   ├── firstpage.html
│   ├── login.html
│   ├── signup.html
│   ├── home.html
│   ├── script.js
│   └── styles.css
│
└── README.md

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

git clone https://github.com/Srivalli0845/smart_fridge.git
cd smart_fridge

---

## 2️⃣ Install Backend Dependencies

cd backend
npm install

---

## 3️⃣ Configure Environment Variables

Create a `.env` file inside the **backend** folder.

Example:

MONGO_URI=your_mongodb_connection_string
PORT=5000
EMAIL=[your_email@gmail.com](mailto:your_email@gmail.com)
PASSWORD=your_app_password

---

## 4️⃣ Start the Backend Server

node server.js

---

## 5️⃣ Open the Frontend

Open this file in your browser:

frontend/firstpage.html

---

# 🔒 Security Practices

* Environment variables stored in `.env`
* Sensitive credentials excluded using `.gitignore`
* Gmail App Password used for email authentication

---

# 📈 Future Improvements

* JWT based authentication
* Password encryption using bcrypt
* Expiry analytics dashboard
* Recipe suggestions for expiring food
* Mobile responsive UI
* Push notifications

---

# 👩‍💻 Authors

**Srivalli Namburi**
**Jyothi Durga Kadali**

---

# ⭐ Support

If you like this project, please give it a **star ⭐ on GitHub**.
