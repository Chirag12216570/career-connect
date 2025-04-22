# Career Connect - Job Application Tracker

Career Connect is a full-stack MERN (MongoDB, Express, React, Node.js) application designed to help job seekers efficiently track their job applications in one organized dashboard.

![Dashboard Preview](./screenshots/dashboard-1.png) <!-- Replace with your actual image paths -->

---

## 🚀 Features

- ✅ Track job applications by status (pending, interview, declined, etc.)
- 📊 Dashboard with statistics on applications
- 📝 Add, update, and delete jobs
- 🔍 Filter and search through job listings
- 🔐 Authentication with JWT (register/login/logout)
- 🎨 Responsive and modern UI

---

## 📸 Screenshots

Add your screenshots in a `/screenshots` folder and reference them here:

- ![Dashboard Screenshot](./screenshots/dashboard-1.png)
- ![Add Job Form](./screenshots/add-job-form.png)
- ![Stats Section](./screenshots/stats-section.png)

---

## 🛠️ Tech Stack

**Frontend**
- React
- Redux Toolkit
- React Router
- Axios

**Backend**
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT for authentication

---

## 📦 Installation & Setup

### Prerequisites

- Node.js (v14+ recommended)
- npm
- MongoDB instance (local or cloud like MongoDB Atlas)

### 1. Clone the Repository

```bash
git clone https://github.com/Chirag12216570/career-connect.git
cd career-connect
# Backend
npm install

# Frontend
cd client
npm install

# Create .env file
PORT=9000
MONGO_URL=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

# Run the app
# Start Backend
npm run server

# In another terminal, start Frontend
cd client
npm start

