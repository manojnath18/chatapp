# 💬 MERN Chat App

A real-time chat application built using the MERN stack with features like user authentication, one-to-one chat, group chat, and instant messaging using **Socket.IO**.

---

## 🚀 Features

- 🔐 **User Authentication**
  - Sign up & log in with JWT token-based authentication
- 💬 **One-to-One Chat**
  - Send and receive messages in real-time
- 👥 **Group Chat**
  - Create group chats, add/remove users
- ⚡ **Real-time Messaging**
  - Built with Socket.IO for live messaging updates
- 🛡️ **Protected Routes**
  - Backend secured with JWT middleware
- 🌐 **Responsive UI**
  - Clean and user-friendly interface built with React

---

## 🛠️ Tech Stack

### Frontend:
- React.js
- Chakra UI
- Axios

### Backend:
- Node.js
- Express.js
- MongoDB + Mongoose
- JWT (JSON Web Token)
- Socket.IO

---

## 📁 Project Structure

root
├── backend
│ ├── config/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ └── server.js
├── frontend
│ ├── public/
│ ├── src/
│ └── build/
└── README.md


---

## ⚙️ Setup Instructions

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/mern-chat-app.git
cd mern-chat-app
```
Setup Backend:
```
cd backend
npm install
```

Create a .env file in backend/ with the following:
```
PORT=5000

MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
NODE_ENV=production
```

Setup Frontend:
```
cd ../frontend
npm install
```

#🚀 Run Locally

Start Backend:
```
cd backend
npm start
```

Start Frontend:
```
cd frontend
npm start
```

🌐 Deployment
You can deploy the frontend to Render, Netlify, or Vercel and the backend to Render or Heroku.

Make sure to:

- Point the frontend API base URL to your deployed backend.

- Use environment variables correctly in production.


🙌 Credits:
Built by MANOJ NATH




