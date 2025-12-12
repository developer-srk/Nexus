# ✨ NEXUS — Premium Productivity Suite

> A modern, glassmorphism-based productivity web app designed for focus, analytics, and progress tracking.

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Version-1.0-blue?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Frontend-HTML%20%7C%20CSS%20%7C%20JavaScript-orange?style=for-the-badge"/>
  <img src="https://img.shields.io/badge/Backend-Spring%20Boot%20%7C%20MySQL-lightgrey?style=for-the-badge"/>
</p>

---

## 🚀 Overview
**Nexus** is a next-generation productivity suite built to help users stay focused, track progress, and stay consistent.  
It features a Pomodoro-style focus mode, analytics dashboard, reward system, and modern UI with glassmorphism and animated gradients.

---

## 🌟 Features
- 🕒 Focus Timer (Pomodoro style)
- 📊 Analytics Dashboard (Daily / Weekly)
- 🎖 Reward & XP System
- 🔐 Login & Register System
- 🌙 Dark / Light Theme Toggle
- ✨ Smooth Animations + Glassmorphism UI
- 📱 Fully Responsive Design

---

## 🧰 Tech Stack

### Frontend
- HTML5  
- CSS3 (Glassmorphism, Animations)  
- JavaScript (Vanilla)  
- Google Fonts  
- FontAwesome  

### Backend (Recommended)
- Spring Boot (Java)  
- MySQL Database  
- REST APIs  
- JWT (optional)

---

## 🗂 Project Structure
Nexus/
│
├── frontend/
│ ├── index.html
│ ├── index2.html
│ ├── login-register.html
│ └── assets/
│ ├── css/
│ ├── js/
│ └── images/
│
├── backend/
│ ├── src/main/java/com/nexus/
│ ├── src/main/resources/
│ └── pom.xml
│
└── README.md


---

## ▶ Running the Frontend

### Option A — Open directly  
Open `frontend/index.html` in your browser.

### Option B — Run with local server  
```bash
cd frontend
python3 -m http.server 8000

### Option C — Node static server
npm install -g serve
serve frontend

### ▶ Running the Backend (Spring Boot + MySQL)
1. Create MySQL Database
CREATE DATABASE temp1;

### 2. Configure application.properties
spring.datasource.url=jdbc:mysql://localhost:3306/temp1
spring.datasource.username=YOUR_USER
spring.datasource.password=YOUR_PASS
spring.jpa.hibernate.ddl-auto=update

### 3. Run the backend
mvn spring-boot:run

### 🔌 Example API Endpoints
POST /api/auth/register
POST /api/auth/login
GET  /api/user/sessions
POST /api/session/start
POST /api/session/complete

### 📦 Deployment
Frontend

Netlify

Vercel

GitHub Pages

Backend

Railway

Render

AWS / Docker

### 🤝 Contributing

Pull Requests are welcome.
For major changes, open an issue first to discuss the feature.

### 📝 License

MIT © 2025 — Developer SRK

If you want an **ultra-premium animated banner**, **badges**, or **dark-themed README**, just tell me — I’ll generate it.
