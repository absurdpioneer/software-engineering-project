# my-pomelo-chat

my-pomelo-chat is a real-time multi-user chat room project developed using Node.js and Socket.io. It supports core instant messaging (IM) features such as user registration and login, real-time messaging, group and friend chat, file uploads, and basic chat room management. This project is ideal for learning, teaching, or quickly building your own chat system.

---

## Features

- User registration and login (JWT authentication/session)
- Real-time message communication (private and group chat)
- Friend adding and contact management
- File upload and download (common file types supported)
- Message history storage (MongoDB/MySQL, selectable)
- Clean and intuitive front-end interface
- Mobile responsive support
- Basic chat room management (e.g., create/disband groups)

---

## Tech Stack

### Frontend

- HTML + CSS + JavaScript
- Socket.io client (optionally upgradeable to React/Vue frameworks)
- Axios (for HTTP communication with backend)
- Modern browser support

### Backend

- Node.js + Express
- Socket.io
- Database: MongoDB or MySQL (choose one or support both)
- JWT (jsonwebtoken, for user authentication)
- Multer (middleware for file uploads)

---

## Project Structure

```
my-pomelo-chat/
├── src/                 # Backend core code
│   ├── api/             # RESTful routes
│   ├── models/          # Database models (user, message, etc.)
│   ├── socket/          # Socket.io message handling
│   ├── utils/           # Utility functions
│   └── index.js         # Service entry point
├── public/              # Front-end static pages and resources
│   ├── index.html
│   └── ...
├── uploads/             # File upload directory
├── package.json
├── README.md
└── ...
```

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-github-username/my-pomelo-chat.git
cd my-pomelo-chat
```

### 2. Install dependencies

```bash
npm install
```

### 3. Database configuration

- Create a new MongoDB or MySQL instance.
- Edit `src/config.js` (or `.env`) and fill in the database connection info.

### 4. Start the backend service

```bash
npm start
# or
node src/index.js
```

### 5. Access the frontend

Open your browser and navigate to:
```
http://localhost:3000
```

Register and log in to experience real-time chat and all features.

---

## Main Configuration

- `src/config.js` or `.env` — database/port/JWT secret, etc.
- `public/` — Front-end pages and resources
- `uploads/` — Directory for uploaded files

---

## Common Scripts

- `npm start` — Start the backend service
- `npm run dev` — (If supported) Hot-reload development
- `npm run lint` — Lint code style (if configured)

---

## LAN Testing

On the same Wi-Fi or local network, you can use phone and computer to log in to the same service address for multi-user chat testing.  
(For public access, you may use tools such as ngrok or cloudflared.)

---

## Contribution & Communication

Feel free to submit issues or PRs! You can reach me via the [issues](https://github.com/absurdpioneer/my-pomelo-chat/issues) page.

---

## License

MIT License

---

> This project is inspired by the excellent [better-chat](https://github.com/XC0703/better-chat?tab=readme-ov-file).
>
> All code is independently implemented and owned by me, for learning and communication purposes only.

---

**Author:** [absurdpioneer](https://github.com/absurdpioneer)  
March 2026
