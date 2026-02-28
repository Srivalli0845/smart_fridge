# 🧊 Smart Fridge App

A full-stack web application to manage refrigerator inventory with secure OTP-based authentication and automated expiry notifications.

---

## 🚀 Features

- 🔐 OTP-based Email Authentication
- ➕ Add / Delete Food Items
- 📅 Track Expiry Dates
- 📧 Automated Email Alerts for Expiring Items
- 👤 User-specific Inventory Management

---

## 🛠️ Tech Stack

### Frontend
- HTML
- CSS
- JavaScript

### Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- Nodemailer

---

## 📂 Project Structure
smart_fridge/
│
├── backend/
│ ├── server.js
│ ├── routes/
│ ├── package.json
│
├── frontend/
│ ├── login.html
│ ├── signup.html
│ ├── home.html
│ ├── script.js
│
└── README.md

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
git clone https://github.com/Srivalli0845/smart_fridge.git
cd smart_fridge

### 2️⃣ Install Backend Dependencies
cd backend
npm install

### 3️⃣ Setup Environment Variables

Create a `.env` file inside backend:
MONGO_URI=mongodb://127.0.0.1:27017/smart_fridge
PORT=5000
EMAIL=your_email@gmail.com

PASSWORD=your_app_password

### 4️⃣ Run Backend Server
node server.js

### 5️⃣ Open Frontend

Open:
frontend/firstpage.html

---

## 🔒 Security Note

- Uses Gmail App Password for secure OTP email delivery
- Environment variables stored securely in `.env`
- `node_modules` excluded using `.gitignore`

---

## 📌 Future Improvements

- JWT-based authentication
- Password hashing (bcrypt)
- OTP expiry timer
- Cloud deployment (Render / Railway)
- Mobile responsive UI

---

## 👩‍💻 Author

**Srivalli Namburi**
**Jyothi Durga Kadali**

---

## ⭐ If You Like This Project

Give it a ⭐ on GitHub!


