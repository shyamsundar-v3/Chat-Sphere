# 🌐 Chat Sphere

![React](https://img.shields.io/badge/React-18-blue?logo=react)
![Node.js](https://img.shields.io/badge/Node.js-Backend-green?logo=node.js)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-brightgreen?logo=mongodb)
![Socket.IO](https://img.shields.io/badge/Socket.IO-RealTime-black?logo=socket.io)
![License](https://img.shields.io/badge/License-MIT-yellow)

A modern full-stack social media platform inspired by Meta's Threads app, built using the **MERN Stack**. Chat Sphere enables users to connect, share posts, engage with content, and communicate in real-time through a seamless and responsive user experience.

---

## ✨ Features

### 🔐 Authentication & Authorization

* User registration and login
* JWT-based authentication
* Secure password hashing with bcrypt
* Protected routes
* Logout functionality

### 👤 User Management

* User profiles
* Profile picture upload
* Edit profile information
* Follow and unfollow users
* View user posts

### 📝 Posts & Interactions

* Create text and image posts
* Delete posts
* Like and unlike posts
* Comment on posts
* Personalized feed
* Responsive user experience

### 💬 Real-Time Messaging

* One-to-one messaging
* Online user status tracking
* Instant communication using Socket.IO

### ☁️ Media Uploads

* Cloudinary integration
* Image upload and storage
* Optimized media delivery

### 🎨 Responsive UI

* Modern design using Chakra UI
* Mobile-friendly interface
* Dark mode support
* Clean and intuitive user experience

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Vite
* Chakra UI
* React Router DOM
* Recoil
* Socket.IO Client

### Backend

* Node.js
* Express.js
* MongoDB Atlas
* Mongoose
* JWT Authentication
* Cookie Parser
* Socket.IO

### Cloud Services

* MongoDB Atlas
* Cloudinary

---

## 📂 Project Structure

```bash
Chat-Sphere/
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── socket/
│   ├── db/
│   ├── server.js
│   └── package.json
│
└── README.md
```

---

## ⚙️ Installation & Setup

### Clone Repository

```bash
git clone https://github.com/shyamsundar-v3/Chat-Sphere.git
cd Chat-Sphere
```

---

### Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file:

```env
PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

Start the backend server:

```bash
npm run dev
```

Backend runs at:

```bash
http://localhost:5000
```

---

### Frontend Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs at:

```bash
http://localhost:3000
```

---

## 🔑 Environment Variables

| Variable              | Description                       |
| --------------------- | --------------------------------- |
| PORT                  | Backend server port               |
| MONGO_URI             | MongoDB Atlas connection string   |
| JWT_SECRET            | Secret key for JWT authentication |
| CLOUDINARY_CLOUD_NAME | Cloudinary cloud name             |
| CLOUDINARY_API_KEY    | Cloudinary API key                |
| CLOUDINARY_API_SECRET | Cloudinary API secret             |

---

## 🗄️ Database Collections

* Users
* Posts
* Comments
* Conversations
* Messages

---

## 🔌 API Highlights

### Authentication

```http
POST /api/users/signup
POST /api/users/login
POST /api/users/logout
```

### Users

```http
GET /api/users/profile/:username
PUT /api/users/update
POST /api/users/follow/:id
```

### Posts

```http
POST /api/posts/create
GET /api/posts/feed
POST /api/posts/like/:id
POST /api/posts/comment/:id
DELETE /api/posts/:id
```

### Messages

```http
POST /api/messages/send/:id
GET /api/messages/:id
```

---

## 📸 Screenshots

### 🏠 Login Page

<img width="1600" height="800" alt="image" src="https://github.com/user-attachments/assets/acbec23f-f387-45e7-9ae8-5342cc5003dd" />


### 👤 User Profile

<img width="1600" height="781" alt="image" src="https://github.com/user-attachments/assets/8c1f1c18-fbd7-4363-9bf9-15f7bd4f9022" />


### 💬 Real-Time Chat

<img width="1600" height="785" alt="image" src="https://github.com/user-attachments/assets/f4986547-e3a4-4811-9503-093f60c8df52" />


---

## 🚀 Future Enhancements

* Push notifications
* Story feature
* Group chats
* Search and discovery
* Post sharing
* Admin dashboard
* AI-powered content recommendations

---

## 🔒 Security

* Password hashing using bcrypt
* JWT authentication
* Protected routes
* Secure cookies
* Input validation

---

## 👨‍💻 Authors

**Shyam Sundar**
https://github.com/shyamsundar-v3


---

## 📜 License

This project is licensed under the MIT License.

⭐ If you found this project useful, consider giving it a star on GitHub!
