# 🚀 MERN Task Manager App

A full-stack **Task Manager** built with the **MERN** (MongoDB, Express.js, React, Node.js) stack — featuring user authentication, task management, Excel report generation, and a modern UI powered by TailwindCSS.

---

## 🗂️ Project Structure

```
task-manager/
├── backend/                # Node.js + Express + MongoDB API
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── middlewares/
├── frontend/Task-Manager/  # React + TailwindCSS frontend
│   └── screenshots/        # App screenshots
```

---

## ✨ Features

- 🔐 User Registration & Login (JWT-based)
- ✅ Task CRUD operations
- 📋 Task filtering & deadline management
- 📊 Interactive charts via Recharts
- 📁 Download reports as Excel files
- 🔒 Protected routes & auth middleware
- 💅 Clean and responsive UI with Tailwind CSS
- 🔔 Toast notifications on actions

---

## ⚙️ Tech Stack

**Backend**
- Node.js + Express
- MongoDB + Mongoose
- JWT Authentication
- Multer (for uploads)
- ExcelJS (for reports)

**Frontend**
- React
- React Router
- Tailwind CSS
- Axios
- Recharts
- React Hot Toast

---

## 🧪 Setup Instructions

### 🔧 Prerequisites
- Node.js & npm
- MongoDB (local or Atlas)

---

### 🛠️ Installation

#### 1. Clone the Repo

```bash
git clone https://github.com/Jhasija9/task-manager.git
cd task-manager
```

#### 2. Backend Setup

```bash
cd backend
npm install
cp .env.example .env
# Fill in your .env file:
# MONGO_URI=your_mongodb_connection_string
# JWT_SECRET=your_jwt_secret
npm run dev   # Runs on http://localhost:5000
```

#### 3. Frontend Setup

```bash
cd frontend/Task-Manager
npm install
npm run dev   # Runs on http://localhost:5173
```

---

## 🔐 Authentication

- JWT token is generated on login and stored in local storage
- All protected routes are guarded with custom Express middleware

---

## 📦 Available Scripts

### Backend
```bash
npm run dev     # Start with nodemon
npm start       # Start production server
```

### Frontend
```bash
npm run dev     # Start Vite dev server
npm run build   # Production build
npm run preview # Preview build
```

---

## 📁 Environment Variables (`.env`)

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```

---

## 📊 Reporting

Visit the **Reports** page after logging in to download your task history as an Excel file. Data is formatted using the **ExcelJS** library.

---

## 📸 Screenshots

**Screenshots**  
<img width="1512" alt="Screenshot 2025-06-27 at 2 38 04 PM" src="https://github.com/user-attachments/assets/1caade9f-628e-4b6b-bf65-b4efd956bde3" />  
<img width="1512" alt="Screenshot 2025-06-27 at 2 35 36 PM" src="https://github.com/user-attachments/assets/ea3e6fa8-357f-4c5c-bcc2-5ba75be07024" />  
<img width="1507" alt="Screenshot 2025-06-27 at 2 36 20 PM" src="https://github.com/user-attachments/assets/45291382-2153-4c68-918d-31bd5de5e1f3" />  
<img width="1512" alt="Screenshot 2025-06-27 at 2 36 50 PM" src="https://github.com/user-attachments/assets/74b069ed-7e38-47f7-aa6d-f78ef6b1415b" />  
<img width="1511" alt="Screenshot 2025-06-27 at 2 37 25 PM" src="https://github.com/user-attachments/assets/95e6ee95-63c5-4d44-a63b-fe0cdbff07fa" />

---

## 🤝 Contribution

Want to improve the project?  
Fork the repo and submit a pull request — contributions are welcome!

---

## 📝 License

Licensed under the MIT License.
