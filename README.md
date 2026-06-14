# 🚀 AI Habit Tracker

An AI-powered Habit Tracking Application built with the MERN Stack (MongoDB, Express.js, React.js, Node.js) and Google Gemini AI. This application helps users build better habits, track daily progress, maintain streaks, and receive personalized AI-driven insights.

## ✨ Features

### 🔐 Authentication

* User Registration & Login
* JWT Authentication
* Secure Password Hashing with bcrypt
* Protected Routes

### 📋 Habit Management

* Create, Edit, Delete Habits
* Archive Habits
* Categorize Habits
* Custom Icons & Colors
* Target Day Selection

### 📅 Daily Tracking

* One-Click Habit Completion
* Daily Progress Monitoring
* Interactive Progress Indicators

### 🔥 Streak Tracking

* Current Streak Calculation
* Longest Streak Records
* Consistency Monitoring

### 📊 Analytics Dashboard

* Weekly Performance Overview
* Habit Completion Statistics
* Category-wise Analysis
* Progress Visualization

### 🗓️ 90-Day Heatmap

* GitHub-Style Activity Heatmap
* Consistency Visualization
* Theme-Aware Design

### 🤖 AI Features (Google Gemini)

* AI Weekly Habit Report
* Personalized Habit Suggestions
* Habit Analysis Chat
* Morning Motivation Messages
* Streak Recovery Plans
* Natural Language Habit Insights

### 🌙 Modern UI/UX

* Responsive Design
* Light & Dark Mode
* Glassmorphism UI
* Mobile-Friendly Layout

---

## 🛠️ Tech Stack

### Frontend

* React.js
* React Router DOM
* Axios
* Tailwind CSS v4
* Context API

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT Authentication
* bcryptjs

### AI Integration

* Google Gemini API

---

## 📂 Project Structure

```bash
AI-Habit-Tracker/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── services/
│   └── App.jsx
│
└── README.md
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/your-username/ai-habit-tracker.git
cd ai-habit-tracker
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

### Environment Variables

Create a `.env` file inside the backend folder:

```env
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
GEMINI_API_KEY=your_gemini_api_key
```

---

## 🎯 Future Improvements

* Email Notifications
* Habit Reminders
* Social Habit Sharing
* Achievement Badges
* Leaderboards
* AI Habit Prediction
* Mobile App Version

---

## 👨‍💻 Author

**Nyusi Patel**

Built to help users stay consistent, productive, and achieve their goals through AI-powered habit tracking.

⭐ If you like this project, don't forget to star the repository!
