# Blogger Application — Full-Stack Blogging Platform

A full-stack blogging platform with a React.js frontend and Node.js/Express backend. Supports user authentication, post creation, editing, and a clean content feed. Built as a foundational project to solidify REST API design and frontend-backend integration patterns.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js, CSS |
| Backend | Node.js, Express |
| Auth | JWT |
| API Testing | REST Client (requests.http) |

---

## ✨ Features

- User registration and login with JWT authentication
- Create, edit, and delete blog posts
- View all posts in a content feed
- Protected routes — only authenticated users can publish content
- Clean separation of frontend and backend services

---

## 🚀 Getting Started

### Prerequisites

- Node.js `16.x` or above

### 1. Backend Setup

```bash
cd Backend
npm install
```

Create a `.env` file:

```
PORT=5000
DB_URL=<your_mongodb_connection_string>
SECRET_KEY=<your_jwt_secret>
```

Start the server:

```bash
node server.js
```

### 2. Frontend Setup

```bash
cd frontend
npm install
npm start
```

The app will be available at `http://localhost:3000`.

---

## 📁 Project Structure

```
Blogger-Application/
├── Backend/        # Node.js REST API
├── frontend/       # React.js UI
└── requests.http   # API test collection
```

---

## 👤 Author

**Ravikiran Pedapalli**  
[Linkedin](https://linkedin.com/in/pedapalli-ravi-kiran-ab5006254)
