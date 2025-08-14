# GoalSetter App

GoalSetter is a **full-stack MERN application** that allows users to register, log in, and set personal goals. It features **user authentication with JWT**, goal management, and a responsive frontend. 
The backend is built with **Node.js, Express, and MongoDB**, and the frontend uses **React**.  

---

## Features

- User registration and login with **JWT authentication**
- Create, read, and manage personal goals
- Responsive React frontend
- RESTful API tested with **Postman**
- Cloud-based database using **MongoDB Atlas**

---

## Technologies Used

- **MongoDB Atlas** – Cloud database
- **Express.js** – Backend framework
- **React.js** – Frontend framework
- **Node.js** – Runtime environment
- **JWT** – JSON Web Token for authentication
- **Postman** – API testing
- **Axios** – HTTP requests from frontend
- **Redux Toolkit** – State management

---

## Installation

### Backend Dependencies
From the root project folder:

```bash
npm install

```bash
cd frontend
npm install

### Run the server backend

```bash
npm run server

API Testing

You can test the backend endpoints using Postman.
Example endpoints:
POST /api/users – Register a new user
POST /api/users/login – Login user
GET /api/goals – Get all goals (requires JWT)
POST /api/goals – Create a new goal (requires JWT)
