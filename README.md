# my-pomelo-chat

my-pomelo-chat is a lightweight real-time chat system built with Node.js and Socket.io. It supports private messaging, group chat, file transfer, and other core IM (Instant Messaging) features. This project is ideal for learning, teaching, or quickly deploying a private chat service.

---

## 📌 Overview

### 🖼 UI Preview

login page：

![Uploading e962f14747513dbcd4fb9ea3a76b37c2.png…]()

private chat：

<img width="633" height="701" alt="e881c2c1596be8cab72799960b80d2b8" src="https://github.com/user-attachments/assets/3ac23826-2815-4f6e-9fe2-8ed9b3649533" />

group chat：

![Uploading 6c4c638742f644e6f05220fc1337ff4e.png…]()

intelligent chat entity：

![Uploading 72b22eb4910eed68f68e0da39126c868.png…]()

---

## 🎯 Purpose

### 🚀 Development Methodology

- Development Model: **Agile (Scrum)**
- Reasons:
  - Rapid validation of core features (real-time messaging, file upload)
  - Flexible for solo development + community contributions
  - Suitable for iterative improvements in learning environments
  - More adaptable than the waterfall model

---

### 🎯 Target Market

- Core Scenarios:
  - Programming education / training
  - Node.js / Socket.io practice
- Secondary Scenarios:
  - Small team communication
  - Temporary chat systems

### 👥 Target Users

- Beginner to intermediate developers
- Programming educators
- Small teams

---

## ✨ Features

- ✅ User registration & login (JWT authentication)
- 💬 Real-time messaging (private & group chat)
- 👥 Friend management
- 📁 File upload & download
- 🗂 Message storage (MongoDB / MySQL)
- 📱 Mobile responsive design
- 🏠 Chat room management

---

## 🛠 Tech Stack

### Frontend

- HTML + CSS + JavaScript
- Socket.io-client
- Axios

### Backend

- Node.js + Express
- Socket.io
- MongoDB / MySQL
- JSON Web Token (JWT)
- Multer (file upload)

---

## 🧠 Core Implementation

- **Real-time Communication**
  - Socket.io publish-subscribe model
  - Private chat via user ID rooms
  - Group chat via group ID rooms

- **Authentication**
  - JWT (HS256)
  - Token attached to Socket context

- **File Handling**
  - Multer upload middleware
  - MD5-based deduplication

- **Data Storage**
  - Indexed by timestamp + user ID for efficient queries

---

## 📂 Project Structure

```
my-pomelo-chat/
├── src/
│   ├── api/
│   ├── models/
│   ├── socket/
│   ├── utils/
│   └── index.js
├── public/
├── uploads/
├── package.json
└── README.md
```

---

## 🚀 Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-github-username/my-pomelo-chat.git
cd my-pomelo-chat
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Configure database

- Use MongoDB or MySQL
- Update `.env` or `config.js`

### 4️⃣ Start the server

```bash
npm start
```

### 5️⃣ Open in browser

http://localhost:3000

---

## 🔧 Development Plan

Requirements → Prototype → Iteration → Testing → Release → Feedback → Next iteration

### 📅 Timeline

| Phase | Time | Description |
|------|------|-------------|
| Planning | 2026.01 | Feature definition |
| V1.0 | 2026.02 | Login + private chat |
| V2.0 | 2026.03 | Group chat + file upload |
| Optimization | 2026.03 | Bug fixes |
| Iteration | 2026.04+ | New features |

---

## 📊 Current Status

- ✅ Core features completed
- ✅ Local deployment supported
- ⚠ No stress testing yet

---

## 🔮 Roadmap

### Short-term

- UI improvements
- Message recall/edit
- Logging system

### Mid-term

- React / Vue integration
- Read/unread status
- Media support

### Long-term

- Distributed deployment
- AI chatbot integration
- Mobile app / mini program

---

## 🎥 Demo Video

https://www.youtube.com/watch?v=wGRbYA840_o
---

## ⚙️ Requirements

### Minimum Server

| Type | Requirement |
|------|------------|
| CPU | 1 core |
| RAM | 1GB |
| Disk | 100MB |

---

## 📦 Dependencies

| Package | Purpose |
|--------|--------|
| express | Web server |
| socket.io | Real-time communication |
| jsonwebtoken | Authentication |
| multer | File upload |
| mongoose/mysql2 | Database |

---

## 🌐 LAN Testing

http://YOUR_IP:3000

---

## 🤝 Contribution

https://github.com/absurdpioneer/my-pomelo-chat/issues

---

## 📜 License

MIT License

---

## 📢 Disclaimer

- For learning and educational use only
- Not intended for direct commercial deployment

---

## 👨‍💻 Author

absurdpioneer  
March 2026
