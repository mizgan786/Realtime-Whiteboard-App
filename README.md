# 🎨 Realtime Whiteboard App

![React](https://img.shields.io/badge/React-Frontend-61DAFB?logo=react)
![Socket.IO](https://img.shields.io/badge/Socket.IO-Realtime-black?logo=socketdotio)
![Node.js](https://img.shields.io/badge/Node.js-Backend-339933?logo=node.js)
![License](https://img.shields.io/badge/Status-Active-success)

Collaborate, sketch, and brainstorm **together in real-time** using **React**, **Node.js**, and **Socket.IO**.

Multiple users can draw simultaneously on a shared whiteboard, with updates synchronized instantly across all connected clients.

---

## ✨ Features

- ✏️ **Real-Time Drawing** – Instantly sync sketches with every connected user.
- 🔌 **Socket.IO Communication** – Low-latency WebSocket-based synchronization.
- ⚛️ **React Frontend** – Responsive and interactive user interface.
- 📂 **Modular Architecture** – Separate frontend and backend for better scalability and maintenance.

---


## 🛠 Prerequisites

Before getting started, ensure you have:

- Node.js
- Git
- VS Code (or any code editor)
- Yarn (`npm install -g yarn`)
- A modern web browser
- Basic knowledge of React

---

## 📦 Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/raiyanz04/Realtime-Whiteboard-App.git
```

### 2️⃣ Install Backend Dependencies

```bash
cd backend
yarn
```

### 3️⃣ Install Frontend Dependencies

```bash
cd ../frontend
yarn
```

---

## 🚀 Running the Application

### Start Backend Server

```bash
cd backend
yarn start
```

### Start Frontend Server

```bash
cd frontend
yarn dev
```

---

## 🔄 How It Works

```
User Draws
      │
      ▼
React Frontend
      │
 Socket.IO Events
      │
      ▼
Node.js Backend
      │
 Broadcast Events
      │
      ▼
All Connected Clients
```

- Users draw on the whiteboard.
- The frontend sends drawing events to the backend using **Socket.IO**.
- The backend broadcasts these events to every connected client.
- All users see the whiteboard update in real time.

---

## 🤝 Contributing

Contributions are always welcome!

Feel free to:

- ⭐ Star the repository
- 🍴 Fork the project
- 🐛 Report issues
- 🚀 Submit pull requests
- 💡 Suggest new features

Whether it's improving the UI, optimizing performance, or enhancing documentation, every contribution is appreciated.

---

### ⭐ If you found this project useful, consider giving it a star!
