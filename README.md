# 🚀 Smart Student Life Dashboard

<p align="center">
  A modern full-stack productivity dashboard built for students to manage tasks, habits, notes, and study sessions.
</p>

---

## 🌟 Overview

Smart Student Life Dashboard is a full-stack web application designed to help students stay productive and organized.

It includes:

- ✅ Task Management
- ✅ Habit Tracking
- ✅ Notes Section
- ✅ Pomodoro Timer
- ✅ Productivity Analytics
- ✅ Dark / Light Mode Toggle
- ✅ REST API Backend

---

## 🛠️ Tech Stack

### Frontend
- ⚛ React (Vite)
- 🎨 Tailwind CSS
- 📦 Axios / Fetch API
- 🌙 Dark Mode (Tailwind class strategy)

### Backend
- 🐍 Flask
- 🔗 REST API
- 🗄 SQLite Database
- 🔐 Authentication (JWT / Session-based)

---

## 📁 Project Structure
Smart-Student-Life-Dashboard/
│
├── frontend/ (React)
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ └── App.jsx
│ └── package.json
│
├── backend/ (Flask)
│ ├── app.py
│ ├── models.py (if separated)
│ └── requirements.txt
│
└── README.md

---

## 🚀 Features

### 🧠 Dashboard
- Clean card-based UI
- Responsive layout
- Real-time productivity stats

### 📋 Task Manager
- Add / Edit / Delete tasks
- Mark as completed
- Stored in database

### 🔁 Habit Tracker
- Track daily habits
- Visual progress indicator

### 📝 Notes
- Create and manage personal notes

### ⏱ Pomodoro Timer
- 25/5 study session timer
- Boosts focus and discipline

### 🌗 Dark / Light Mode
- Smooth theme transition
- Tailwind CSS dark mode strategy

---

## 🔌 API Endpoints (Backend)

| Method | Endpoint | Description |
|--------|----------|------------|
| GET | /api/tasks | Fetch all tasks |
| POST | /api/tasks | Create new task |
| PUT | /api/tasks/:id | Update task |
| DELETE | /api/tasks/:id | Delete task |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/AbhijitCoder/Smart-Student-Life-Dashboard.git
