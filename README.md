# Full Stack Authentication Project

A full stack authentication application built using React, Node.js, Express, and MongoDB Atlas.  
This project implements secure user registration, login, JWT authentication, and protected routes.

---

## 🚀 Features

- register a new user
- login with credentials
- jwt token stored in localStorage
- dashboard protected using token
- logout clears token

---

## 🛠 Tech Stack

### Frontend
- React (Vite)
- React Router DOM
- Axios

### Backend
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- JSON Web Token (JWT)
- bcrypt

---

## 📁 Project Structure

frontend/
- React frontend application
- Login and Register pages
- Protected Dashboard

backend/
- Node.js + Express server
- Authentication APIs
- MongoDB connection
- JWT token generation

---

## ⚙️ How to Run the Project Locally

### 1️⃣ Backend Setup

cd backend  
npm install  
npx nodemon server.js  

Backend runs on:  
http://localhost:5000  

---

### 2️⃣ Frontend Setup

cd frontend  
npm install  
npm run dev  

Frontend runs on:  
http://localhost:5179  

---

## 🔐 Authentication Flow

1. user registers with email and password  
2. password is hashed using bcrypt  
3. user logs in with credentials  
4. backend verifies user and generates jwt token  
5. token stored in localStorage  
6. dashboard accessible only with valid token  
7. logout removes token and redirects to login  

---

## 📌 Key Concepts Used

- REST API development
- JWT authentication
- Password hashing
- Protected routes
- MongoDB Atlas cloud database
- Full stack integration

---

## 👤 Author

Saii Pallapati

---

## 📂 Repository

Hosted on GitHub
