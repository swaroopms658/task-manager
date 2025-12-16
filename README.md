# MERN Task Manager

A simple Task Manager application built with the MERN stack (MongoDB, Express, React, Node.js).

## Live Links
- **Frontend (Vercel):** https://task-manager-dun-psi-13.vercel.app/
- **Backend (Render):** https://task-manager-juu9.onrender.com/tasks

## Features
- Add new tasks
- View all tasks
- Delete tasks
- Persistent data using MongoDB

## Tech Stack
- **Frontend:** React, CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB Atlas

## API Endpoints
| Method | Endpoint | Description |
| :--- | :--- | :--- |
| POST | `/tasks` | Add a new task |
| GET | `/tasks` | Retrieve all tasks |
| DELETE | `/tasks/:id` | Delete a specific task |

## Setup Instructions

### 1. Backend
```bash
cd backend
npm install
# Create a .env file with MONGO_URI
node server.js
