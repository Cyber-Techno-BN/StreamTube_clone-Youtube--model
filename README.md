# 📺 StreamTube – YouTube Clone

StreamTube is a **YouTube clone application** that replicates the core features of YouTube, including video uploads, streaming, likes/dislikes, subscriptions, comments, and user authentication.  

This project is built with a **MERN stack (MongoDB, Express, React, Node.js)** and styled with modern UI libraries for a responsive and engaging experience.  

---

## 🎥 Demo

https://github.com/user-attachments/assets/871d19b8-2461-40d6-9d3b-f4c7233a27c5


## 🚀 Features

- 🔐 **Authentication & Authorization**
  - Sign up, Login with JWT Authentication
  - Google OAuth integration (optional)
  - Password encryption using bcrypt

- 📹 **Video Management**
  - Upload videos with thumbnails
  - Stream videos in multiple qualities
  - Like / Dislike videos
  - Watch history & recommendations

- 👥 **User Interaction**
  - Comment system with nested replies
  - Subscribe / Unsubscribe channels
  - User profile pages with playlists & uploads

- 🔎 **Search & Discovery**
  - Search videos by title, tags, or category
  - Recommended videos based on history

- 📱 **Responsive Design**
  - Optimized for desktop, tablet, and mobile

---

## 🛠️ Tech Stack

**Frontend**
- React.js (or Next.js)
- Redux Toolkit (state management)
- Tailwind CSS / Material UI

**Backend**
- Node.js + Express.js
- MongoDB + Mongoose
- Multer (video uploads)
- JWT Authentication

**Other Tools**
- Cloudinary / AWS S3 (storage)
- FFmpeg (video processing)

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/streamtube.git
cd streamtube

### 2️⃣ Backend Setup

  cd backend
  npm install

Create a .env file in the backend/ directory:

  PORT=5000
  MONGO_URI=your_mongodb_connection_string
  JWT_SECRET=your_secret_key
  CLOUDINARY_API_KEY=your_cloudinary_key
  CLOUDINARY_API_SECRET=your_cloudinary_secret

### 3️⃣ Frontend Setup

  cd frontend
  npm install
  npm start
---

🤝 Contributing

  - Contributions are welcome!

  - Fork the repo

  - Create a new branch

  - Commit changes

  - Open a pull request

---
📜 License

MIT License © 2025


🖤 Built by Bharath B

"Design. Develop. Deliver."
