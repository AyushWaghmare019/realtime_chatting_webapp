# Real-Time One-to-One Chatting App 💬

A **responsive real-time one-to-one chatting application** with a modern UI and secure user authentication. Built using the MERN stack with **Socket.IO** for real-time communication and **Material UI** for design.

## ✨ Features

- 🔒 **User Authentication** – Secure sign-up and login with protected chat routes
- 💬 **One-to-One Messaging** – Real-time chat between users using WebSockets
- 🌐 **Responsive Design** – Mobile-friendly and clean UI with Material UI
- 🟢 **Live Updates** – Instantly reflects sent and received messages without page refresh
- 📜 **Chat History** – Stored in MongoDB for persistence

## 🛠️ Tech Stack

- **Frontend:** ReactJS, Material UI, Socket.IO Client
- **Backend:** Node.js, Express.js, Socket.IO Server
- **Database:** MongoDB (Mongoose)
- **Authentication:** JWT-based auth, bcrypt password hashing

## 🚀 Getting Started

### Prerequisites

- Node.js (v14+)
- MongoDB (local or Atlas)

### Clone and Setup

```bash
# Clone the repository
git clone https://github.com/AyushWaghmare019/realtime_chatting_webapp.git
cd realtime_chatting_webapp

# Install client and server dependencies
cd client
npm install
cd ../server
npm install

# In one terminal (for backend)
cd server
npm start

# In another terminal (for frontend)
cd client
npm start
