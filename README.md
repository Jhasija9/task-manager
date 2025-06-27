**MERN Task Manager App**
A full-stack Task Manager built with the MERN (MongoDB, Express.js, React, Node.js) stack, featuring user authentication, task CRUD operations, and downloadable reports in Excel format.

**Project Structure**
bash

├── backend/            # Node.js + Express + MongoDB API
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middlewares/
│   └── server.js
│
└── frontend/Task-Manager/   # React + TailwindCSS frontend
**Features**
User Registration & Login (JWT-based)

Create, Read, Update, Delete (CRUD) tasks

Task listing with filtering

Download task reports as Excel files

Protected routes and middleware validation

Responsive UI with Tailwind CSS

Interactive charts via Recharts

🛠 Tech Stack
Backend:
Node.js

Express

MongoDB & Mongoose

**JWT Authentication
**
Multer (for file handling)

ExcelJS (for reports)

Frontend:
React

React Router

Tailwind CSS

Axios

Recharts

React Hot Toast for notifications

**Installation**
Prerequisites
Node.js & npm

MongoDB running locally or Atlas URL

**Clone the Repository**
bash
Copy
Edit
git clone https://github.com/Jhasija9/task-manager.git
cd task-manager
1. Backend Setup
bash
Copy
Edit
cd backend
npm install
cp .env.example .env   # Add MongoDB URI and JWT_SECRET
npm run dev            # Runs on http://localhost:5000
2. Frontend Setup
bash
Copy
Edit
cd frontend/Task-Manager
npm install
npm run dev            # Runs on http://localhost:5173
📂 Environment Variables (.env)
Inside backend/.env:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

**Reporting**
Visit the Reports page after logging in to download your task history in Excel format. Reports are generated using the ExcelJS library.

Available Scripts
Backend
npm run dev – Start server with nodemon

npm start – Start server

Frontend
npm run dev – Start Vite dev server

npm run build – Production build

npm run preview – Preview built app

**Authentication**
JWT token is generated on login and stored in local storage

Protected routes are handled via custom Express middleware

**Screenshots**
You can add some images or screen recordings here showing task creation, filtering, and Excel report downloads.

