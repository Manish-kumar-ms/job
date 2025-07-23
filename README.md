# 🧑‍💼 JOB HUNT - Job Portal Application

A full-stack web application that allows companies to post job listings and candidates to browse and apply for jobs. This platform bridges the gap between employers and job seekers with an intuitive and modern interface.

---

## 🌐 Live Demo

🔗 [Live Site](https://your-live-site-link.com) *(Replace with your actual deployed URL)*

---

## 🚀 Features

### 👤 Job Seeker
- Sign up / Login
- Browse and search jobs
- Apply to job postings
- View applied job history

### 🏢 Company
- Register / Login
- Post new jobs
- View list of job applicants
- Edit or delete job listings

---

## 🛠️ Tech Stack

| Layer        | Technology                              |
|--------------|------------------------------------------|
| Frontend     | React.js, Tailwind CSS, React Router DOM |
| Backend      | Node.js, Express.js                      |
| Database     | MongoDB (via Mongoose)                   |
| State Mgmt   | React Context API                        |
| Auth         | JSON Web Token (JWT)                     |
| Environment  | dotenv                                   |

---

## 📁 Project Structure

\`\`\`
job-hunt/
├── client/                # React Frontend
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── context/
│   │   └── App.js
│   └── package.json
├── server/                # Node.js Backend
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── index.js
└── README.md
\`\`\`

---

## ⚙️ Getting Started

### 📦 Prerequisites

- Node.js installed
- MongoDB connection URI (MongoDB Atlas or local)

### 🔧 Backend Setup

\`\`\`bash
cd server
npm install
# Create a .env file
touch .env
# Add the following:
PORT=8000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
npm run dev
\`\`\`

### 🎨 Frontend Setup

\`\`\`bash
cd client
npm install
npm start
\`\`\`

---

## 🔐 Environment Variables

Inside \`server/.env\`:

\`\`\`env
PORT=8000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/jobhunt
JWT_SECRET=your_jwt_secret
\`\`\`

---







