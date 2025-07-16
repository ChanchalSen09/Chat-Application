# 💬 Full Stack Scalable Chat Application

A **real-time, scalable, production-ready chat app** built with **React + TypeScript** on the frontend and **Django + Django Channels + PostgreSQL + Redis** on the backend. Supports group chats, end-to-end private messaging, media sharing, user profiles, privacy settings, and auto-expiring messages.

> ⚡ Designed for performance (5,000 active users, 30,000 total), developer-friendly structure, and real-world deployment scenarios.


## 🚀 Features

### 🔐 Authentication
- JWT-based secure login/signup
- User session management
- Centralized auth store

### 💬 Messaging
- 1-1 and group chats
- Auto-scroll and typing indicators
- Socket.io (WebSocket) real-time chat
- Expiring messages support

### 📂 Media Support
- Upload: images, docs, music, videos
- View/download media in chat
- Progress updates via WebSocket

### 🧑 Profile & Privacy
- Custom profile, status & about
- Privacy toggles: last seen, read receipts

### 🛠️ Settings
- Notifications, mute, block
- Theme switching (planned)

### 📈 Scalable Architecture
- 30k total users / 5k active users
- Redis PubSub for scalable WebSocket
- Optimized query design and state management

---

## 🧱 Tech Stack

### 🎯 Frontend
- **React 18** + **TypeScript**
- **Tailwind CSS** + `clsx` for conditional styling
- **React Router v6**
- **Zustand** for state management
- **Socket.IO Client**
- **Axios** + Centralized API Layer
- **Biome.js** for linting & formatting
- **React Toastify** for notifications

### ⚙️ Backend
- **Django 5** with **Django Rest Framework**
- **Django Channels** (WebSockets)
- **Redis** (PubSub for scaling sockets)
- **PostgreSQL** as main DB
- **Celery + Redis** (for async media handling)
- **Swagger/OpenAPI** documentation via `drf-yasg`

---

> ✅ Biome is used instead of Prettier/ESLint for formatting and linting.

## 🧪 Quality Highlights

- ✅ **Centralized error handling**
- ✅ **Feature-based modular frontend**
- ✅ **API abstraction layer** via `services/`
- ✅ **Reusable components**
- ✅ **Real-time progress feedback**
- ✅ **Optimized database queries**
- ✅ **Backend-first architecture**
- ✅ **Scalable WebSocket system using Redis**
- ✅ **Industry-level folder structure & naming conventions**


---

## 🧰 Tools Used

- [Biome](https://biomejs.dev) – unified formatter + linter
- [Socket.IO](https://socket.io/)
- [React Router](https://reactrouter.com/)
- [Zustand](https://zustand-demo.pmnd.rs/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Django Channels](https://channels.readthedocs.io/)
- [Swagger](https://drf-yasg.readthedocs.io/)

---

## ✨ Future Enhancements

- ✅ Light/dark theme
- ✅ Message delivery & read status
- ✅ User presence (online/offline)
- ✅ Search and archive messages
- ⏳ Mobile PWA support
- ⏳ Group admin/moderator roles
- ⏳ Full Docker & CI/CD setup

---

## 🧑‍💻 About Me

Hi, I'm **Chanchal Sen** – a Full Stack Developer with strong backend and system design skills. This project reflects my commitment to **scalable architectures**, **clean coding**, and **industry-level practices**.

📫 [LinkedIn](https://www.linkedin.com/in/chanchal09/) | [GitHub](https://github.com/ChanchalSen09)


