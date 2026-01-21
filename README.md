# 🏋️ Elite Edge Fitness — Full-Stack Gym Web Application

A full-stack gym landing web application built with React (frontend) and Node.js + Express (backend).
The project demonstrates real-world frontend–backend integration, responsive UI design, and server-side handling of user data via email delivery.

## 📌 Overview

Elite Edge Fitness is a full-stack web application that simulates a real gym website.
It includes a modern frontend interface for users and a backend server that processes form submissions and delivers messages to the admin via email.

### The project focuses on:

- Component-based frontend architecture

- Responsive UI/UX design

- API-based communication between frontend and backend

Handling real user input on the server side

## ✨ Features
### Frontend (React)

- Responsive gym landing page

- Hero section with call-to-action

- Workout sessions & bootcamps showcase

- Pricing plans section

- Image gallery

- BMI Calculator

- Accepts height, weight, and gender

- Calculates BMI and shows result via alert

- Contact form with validation and user feedback

  ### Backend (Node.js + Express)

- REST API endpoint for contact form submission

- Server-side email handling using NodeMailer

-  Secure configuration using environment variables

- CORS-enabled API for frontend communication

### 🔁 Data Flow (Important)

~~~
User (Frontend Form)
        ↓
React (Axios Request)
        ↓
Express API (Backend)
        ↓
NodeMailer
        ↓
Admin Email Inbox
~~~


User data is processed on the backend before being delivered via email, demonstrating real backend responsibility and logic.

## 🛠️ Tech Stack
### Frontend

- React (Vite)

- JavaScript

- CSS

- React Router DOM

- Axios

- React Toastify

- React Spinners

- Lucide React (icons)

### Backend

- Node.js

- Express.js

- NodeMailer

- CORS

- Dotenv

## 📂 Project Structure
```
Frontend/
 ├─ public/
 ├─ src/
 │   ├─ components/
 │   │   ├─ Hero.jsx
 │   │   ├─ Navbar.jsx
 │   │   ├─ WorkoutSessions.jsx
 │   │   ├─ Gallery.jsx
 │   │   ├─ Pricing.jsx
 │   │   ├─ BMIcalculator.jsx
 │   │   ├─ Contact.jsx
 │   │   └─ Footer.jsx
 │   ├─ App.jsx
 │   ├─ App.css
 │   └─ main.jsx
 ├─ index.html
 ├─ vite.config.js
 └─ package.json



Backend/
 ├─ utils/
 │   └─ sendEmail.js
 ├─ app.js
 ├─ config.env
 └─ package.json
```

## ⚙️ Installation & Setup
### 1️⃣ Clone the repository
git clone https://github.com/your-username/elite-edge-fitness.git

### 2️⃣ Frontend Setup
cd frontend
npm install
npm run dev

### 3️⃣ Backend Setup
cd backend
npm install
npm start

Create a config.env file inside the backend directory:


PORT=5000
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_app_password


## 📸 Screenshots

<img width="1896" height="854" alt="image" src="https://github.com/user-attachments/assets/dea6cb74-2840-4f0b-aa9d-0fe523dc0d86" />

<img width="800" height="842" alt="image" src="https://github.com/user-attachments/assets/2fb69d62-467d-4679-8270-6c76d20e50d1" />

<img width="800" height="843" alt="image" src="https://github.com/user-attachments/assets/d3a315d7-eab5-4cd7-8666-f5bfbc69788e" />


<img width="1657" height="852" alt="image" src="https://github.com/user-attachments/assets/ef144aa4-9be9-4332-8c5f-2e4e4b6676f1" />

<img width="1812" height="813" alt="image" src="https://github.com/user-attachments/assets/4d110175-37a7-43d4-9e0d-ac4fac053930" />

<img width="1693" height="756" alt="image" src="https://github.com/user-attachments/assets/ab10fe83-3a53-4e9d-8f8e-4698e1369437" />





##  🚧 Challenges & Learnings

- Solving layout scaling issues across different screen sizes

- Managing responsive typography and spacing

- Connecting frontend forms to backend APIs

- Implementing server-side email handling

- Structuring a project with both frontend and backend codebases

## 🚀 Future Improvements

- Add database integration for message storage

- Improve BMI calculator with detailed health insights

- Add authentication and admin dashboard

- Deploy frontend and backend

- Enhance accessibility and animations

## 👤 Author

 Designed & Developed by Moumoni
