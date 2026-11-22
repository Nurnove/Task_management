
# Task Management System

A web-based task management application developed using Python and Django with PostgreSQL. It helps users organize their daily tasks, manage deadlines, and track task progress through an interactive dashboard.

## 📌 Project Overview

The Task Management System is designed to simplify personal task organization and improve productivity.

Users can create and manage tasks, monitor their progress, and keep track of deadlines through a structured web application.

This is an individual academic project developed to practice web application development, database management, and backend programming.

## ✨ Features

### 👤 User Authentication
- User Registration
- User Login
- User Authentication

### 📋 Task Management
- Create New Tasks
- View Existing Tasks
- Update Task Information
- Delete Tasks
- Manage Task Deadlines
- Track Task Status

### 📊 Dashboard
- Centralized Task Dashboard
- Organized Task Overview
- Task Progress Monitoring

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Backend Programming |
| Django | Web Framework |
| PostgreSQL | Database Management |
| HTML | Page Structure |
| CSS | Styling |
| JavaScript | Frontend Interaction |
| Tailwind CSS | UI Styling |

## 📂 Project Structure

```text
Task_management/
│
├── core/
├── tasks/
├── users/
├── task_management/
│
├── static/
│   └── css/
│
├── manage.py
├── requirements.txt
├── package.json
├── tailwind.config.js
│
└── README.md
```

## ⚙️ Installation & Setup

Follow these steps to run the project locally.

### 1. Clone the Repository

```bash
git clone https://github.com/Nurnove/Task_management.git
cd Task_management
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

### 3. Activate the Virtual Environment

**Windows:**

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

### 5. Configure PostgreSQL

- Install and start PostgreSQL.
- Create a PostgreSQL database.
- Configure database credentials in the Django settings or environment variables.
- Ensure the required PostgreSQL driver is installed.

### 6. Apply Database Migrations

```bash
python manage.py makemigrations
python manage.py migrate
```

### 7. Run the Development Server

```bash
python manage.py runserver
```

Open your browser and visit:

http://127.0.0.1:8000/

## 📸 Screenshots

Screenshots of the application will be added here.

## 🎯 Project Objectives

- Practice Django-based web development.
- Understand relational database integration using PostgreSQL.
- Implement user authentication.
- Develop CRUD operations.
- Improve task organization and productivity.

## 👨‍💻 Developer

**Nurnove**

Computer Science & Engineering Student

GitHub: https://github.com/Nurnove

## 📄 License

This project was developed for educational purposes.
