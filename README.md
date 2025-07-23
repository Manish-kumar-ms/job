# 🧑‍💼 Tech Hire - Job Portal App

A modern and dynamic job portal application that connects job seekers with employers. Companies can post job listings, and users can browse and apply with ease.

## 🌐 Live Demo

- **Live**: [https://job-backend-9961.onrender.com](https://job-backend-9961.onrender.com)  


---

## ✨ Features

- 🔐 **Authentication**: Secure login and signup using JWT  
- 📝 **Job Posting**: Companies can post, edit, and delete job openings  
- 🔍 **Job Search**: Users can browse, search, and filter job listings  
- 📄 **Apply for Jobs**: Easy job application system with history tracking  
- 🧠 **State Management**: Context API for efficient global state handling  

---

## 🛠 Tech Stack

**Frontend:**

- React.js  
- Tailwind CSS  
- Axios  
- React Router DOM  
- Context API  

**Backend:**

- Node.js  
- Express.js  
- MongoDB (with Mongoose)  
- JWT Authentication  

---

## 📁 Project Structure

```
job-hunt/
├── client/               # React Frontend
│   ├── public/
│   └── src/
│       ├── components/
│       ├── pages/
│       ├── context/
│       └── App.jsx
├── server/               # Express Backend
│   ├── models/
│   ├── routes/
│   ├── controllers/
│   └── index.js
├── .env
├── README.md
└── package.json
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js & npm  
- MongoDB Atlas account  

### Installation

```bash

# Install backend dependencies
cd server
npm install

# Install frontend dependencies
cd ../client
npm install
```

---

## 🔐 Environment Variables

Create a `.env` file inside the `server/` directory:

```env
PORT=
MONGODB_URL=
JWT_SECRET=
```

---

## 📦 Backend API Routes

### **Auth Routes**

| Method | Route      | Description        |
|--------|------------|--------------------|
| POST   | `/signup`  | Register new user  |
| POST   | `/signin`  | Authenticate user  |
| GET    | `/logout`  | Logout user        |

### **Job Routes**

| Method | Route              | Description                     |
|--------|--------------------|---------------------------------|
| GET    | `/jobs`            | Get all job listings            |
| POST   | `/jobs`            | Post a new job                  |
| PUT    | `/jobs/:id`        | Edit an existing job            |
| DELETE | `/jobs/:id`        | Delete a job                    |
| POST   | `/jobs/apply/:id`  | Apply to a job by job ID        |

---

## 🧠 How it Works

- Users sign up or log in  
- Job seekers can browse and apply to jobs  
- Employers can post and manage job listings  
- All data is stored in MongoDB  
- Context API manages global app state (auth, jobs, etc.)  

---

## 🧪 Test Account

You can use the following test account to try the app without signing up:

```json
{
  "email": "p@gmail.com",
  "password": "1234"
}
```

---

## 👨‍💻 Author

**Manish Kumar**
