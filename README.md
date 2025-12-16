# Task Manager

A simple, lightweight task manager for creating, organizing, and tracking tasks. This repository provides a full-stack MERN application (MongoDB, Express, React, Node.js) that is easy to run, extend, and ship — suitable for a small personal project, demo, or starter template.

> **NOTE:** This project was built as part of a technical assessment to demonstrate CRUD operations, database integration, and cloud deployment.

---

## Features

* Create, read, and delete (CRUD) tasks
* Real-time list updates fetched from MongoDB
* Responsive UI that works on desktop and mobile
* RESTful API architecture
* Local persistence via MongoDB Atlas (cloud)
* Designed to be easy to extend

---

## Demo

* **Live Frontend (Vercel):** [https://task-manager-dun-psi-13.vercel.app/](https://task-manager-dun-psi-13.vercel.app/)
* **Live Backend API (Render):** [https://task-manager-juu9.onrender.com](https://task-manager-juu9.onrender.com)

---

## Tech Stack

* **Backend:** Node.js + Express
* **Frontend:** React (Create React App)
* **Database:** MongoDB Atlas (Cloud)
* **Styling:** CSS3
* **Deployment:** Vercel (Frontend), Render (Backend)

---

## Prerequisites

* Git
* Node.js (>= 14) and npm
* A MongoDB Atlas connection string (URI)

---

## Quick Start

### Clone the Repository

```bash
git clone https://github.com/swaroopms658/task-manager.git
cd task-manager
```

---

### Run Backend

The backend runs on port **5000** by default.

```bash
cd backend
# install dependencies
npm install

# start server
node server.js
```

Server running at: [http://localhost:5000](http://localhost:5000)

> Make sure your MongoDB Atlas URI is configured in your environment variables (e.g., `.env`).

---

### Run Frontend

The frontend runs on port **3000** by default. Open a new terminal for this.

```bash
cd frontend
# install dependencies
npm install

# start react app
npm start
```

Frontend running at: [http://localhost:3000](http://localhost:3000)

---

## Environment Variables

Create a `.env` file inside the **backend** folder and add:

```env
MONGO_URI=your_mongodb_atlas_connection_string
PORT=5000
```

---

## API Endpoints (Sample)

* `GET /tasks` → Fetch all tasks
* `POST /tasks` → Create a new task
* `DELETE /tasks/:id` → Delete a task

---

## Folder Structure

```
task-manager/
│
├── backend/
│   ├── models/
│   ├── routes/
│   ├── server.js
│   └── package.json
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
└── README.md
```

---

## Future Improvements

* Update task functionality (PUT)
* Task categories and filters
* User authentication
* Due dates and reminders
* Better UI/UX enhancements

---

## License

This project is open-source and available under the **MIT License**.

---

## Author

**Swaroop MS**
GitHub: [https://github.com/swaroopms658](https://github.com/swaroopms658)
