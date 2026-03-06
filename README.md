# Task Manager REST API

## Description
This project is a Task Management REST API built using Node.js, Express.js, and MongoDB. It supports JWT authentication and full CRUD operations for tasks.

## Features
- User Registration
- User Login with JWT
- Create Task
- View Tasks
- Update Task
- Delete Task

## Tech Stack
Node.js  
Express.js  
MongoDB  
JWT Authentication

## Installation

1. Clone the repository

git clone https://github.com/YOURUSERNAME/task-manager-api.git

2. Install dependencies

npm install

3. Add environment variables

Create a .env file

MONGO_URI=mongodb://127.0.0.1:27017/taskmanager
JWT_SECRET=your_secret_key

4. Run server

npm run dev

Server runs on:

http://localhost:5000

## API Endpoints

POST /api/auth/register  
POST /api/auth/login  

POST /api/tasks  
GET /api/tasks  
PUT /api/tasks/:id  
DELETE /api/tasks/:id
