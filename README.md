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

git clone https://github.com/Jhasija9/task-manager.git
cd task-manager
1. Backend Setup

cd backend
npm install
cp .env.example .env   # Add MongoDB URI and JWT_SECRET
npm run dev            # Runs on http://localhost:5000
2. Frontend Setup

cd frontend/Task-Manager
npm install
npm run dev            # Runs on http://localhost:5173
**Environment Variables (.env)**
Inside backend/.env:



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
<img width="1512" alt="Screenshot 2025-06-27 at 2 38 04 PM" src="https://github.com/user-attachments/assets/1caade9f-628e-4b6b-bf65-b4efd956bde3" />
<img width="1512" alt="Screenshot 2025-06-27 at 2 35 36 PM" src="https://github.com/user-attachments/assets/ea3e6fa8-357f-4c5c-bcc2-5ba75be07024" />
<img width="1507" alt="Screenshot 2025-06-27 at 2 36 20 PM" src="https://github.com/user-attachments/assets/45291382-2153-4c68-918d-31bd5de5e1f3" />
<img width="1512" alt="Screenshot 2025-06-27 at 2 36 50 PM" src="https://github.com/user-attachments/assets/74b069ed-7e38-47f7-aa6d-f78ef6b1415b" />
<img width="1511" alt="Screenshot 2025-06-27 at 2 37 25 PM" src="https://github.com/user-attachments/assets/95e6ee95-63c5-4d44-a63b-fe0cdbff07fa" />

