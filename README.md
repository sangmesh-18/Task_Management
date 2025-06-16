# 📝 Task Manager Backend

This is a backend API for a Task Management application built with Node.js, Express, MongoDB, and JWT authentication.

## 🚀 Features

- User Registration & Login
- JWT-based Authentication
- Create, Read, Update, Delete Tasks
- Role-based access per user

## 📁 API Endpoints

### Auth
- `POST /api/auth/register` – Register user
- `POST /api/auth/login` – Login user

### Tasks (Protected)
- `GET /api/tasks` – Get all tasks of the logged-in user
- `POST /api/tasks` – Create a new task
- `PUT /api/tasks/:id` – Update a task
- `DELETE /api/tasks/:id` – Delete a task

## ⚙️ Setup Instructions

```bash
git clone <repo-url>
cd task-manager-backend
npm install
cp .env.example .env
# Fill in your MongoDB URI and JWT secret
npm run dev
```

## 📦 Tech Stack

- Node.js
- Express
- MongoDB
- Mongoose
- JWT
- bcrypt.js
