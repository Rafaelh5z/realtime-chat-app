<div align="center">

# 💬 Real-Time Chat App

**A full-stack real-time messaging platform — React + Next.js frontend and Node.js backend with WebSockets**

[![React](https://img.shields.io/badge/REACT-61DAFB?style=flat-square&logo=react&logoColor=black)](https://reactjs.org)
[![Next.js](https://img.shields.io/badge/NEXT.JS-000000?style=flat-square&logo=nextdotjs&logoColor=white)](https://nextjs.org)
[![Node.js](https://img.shields.io/badge/NODE.JS-339933?style=flat-square&logo=nodedotjs&logoColor=white)](https://nodejs.org)
[![Socket.io](https://img.shields.io/badge/SOCKET.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)](https://socket.io)
[![JavaScript](https://img.shields.io/badge/JAVASCRIPT-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

</div>

---

## 📌 Overview

A real-time messaging web application with a decoupled architecture — a Next.js frontend for the chat interface and a Node.js backend handling WebSocket connections for instant message delivery. Built as a monorepo with both the client and server living in the same repository.

---

## ✨ Features

- 💬 Real-time messaging via WebSockets
- 🏠 Multi-room chat support
- 👤 User presence — online/offline status
- 📱 Responsive UI optimized for desktop and mobile
- ⚡ Instant message delivery with Socket.io
- 🔄 SSR-ready with Next.js

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Frontend | React + Next.js |
| Backend | Node.js |
| Real-time | Socket.io |
| Language | JavaScript |
| Styling | CSS |

---

## 📁 Project Structure

```
├── client/             # Next.js + React frontend
│   ├── pages/          # Next.js pages and routing
│   ├── components/     # Reusable React components
│   └── styles/         # CSS styles
│
└── server/             # Node.js backend
    ├── index.js        # Server entry point
    └── socket/         # WebSocket event handlers
```

---

## 🚀 Getting Started

### Prerequisites

- Node.js 16+
- npm or yarn

### Backend setup

```bash
cd server

# Install dependencies
npm install

# Start the server
npm start
```

Server runs at `http://localhost:3001`

### Frontend setup

```bash
cd client

# Install dependencies
npm install

# Start development server
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

---

## 👤 Author

**Rafael Herrera** · [GitHub](https://github.com/Rafaelh5z) · [LinkedIn](https://linkedin.com/in/rafael-herrera-sanchez)
