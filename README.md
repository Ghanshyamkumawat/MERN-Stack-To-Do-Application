# MERN To-Do Application

A full-stack To-Do Management application built using the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**.  
This application allows users to register, log in, manage tasks, and securely store data using MongoDB.

---

## Features

### User Authentication
- User Registration
- User Login
- JWT Authentication
- Password Encryption using bcrypt
- Protected Routes
- Forgot Password functionality using Email

### Task Management
- Create Tasks
- View Tasks
- Update Tasks
- Delete Tasks
- Store task history in MongoDB

### Frontend Features
- Responsive UI
- Material UI Components
- React Router Navigation
- Axios API Integration
- Date handling using Moment.js

### Backend Features
- REST API
- Express.js Server
- MongoDB Database Connection
- Authentication Middleware
- Environment Variable Support
- Email Service using Nodemailer

---

# Technology Stack

## Frontend
- React.js
- React Router DOM
- Axios
- Material UI (MUI)
- Emotion Styling
- Moment.js

## Backend
- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT
- bcrypt
- Nodemailer
- Validator
- dotenv

---

# Project Structure 

```bash
mern-todo-app-master/
│
├── backend/
│   │
│   ├── controllers/
│   │   ├── forgotPasswordController.js
│   │   ├── taskController.js
│   │   └── userController.js
│   │
│   ├── middleware/
│   │   └── requireAuth.js
│   │
│   ├── models/
│   │   ├── taskModel.js
│   │   └── userModel.js
│   │
│   ├── routes/
│   ├── .env
│   ├── server.js
│   └── package.json
│
├── frontend/
│   │
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── ...
│
└── README.md
