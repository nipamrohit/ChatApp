# ✨ Full Stack Realtime Chat App ✨

![Demo Screenshot](/frontend/public/screenshot-for-readme.png)

A feature-rich full stack real-time chat application built using the **MERN** stack, **Socket.io**, **Tailwind CSS**, and **DaisyUI**.

---

## 🚀 Features

- ⚙️ **Tech Stack**: MongoDB, Express, React, Node.js, Socket.io, Tailwind CSS, DaisyUI
- 🔐 **Authentication & Authorization** using **JWT**
- 💬 **Real-time Messaging** powered by **Socket.io**
- 🟢 **Online User Presence**
- 🌍 **Global State Management** with **Zustand**
- 🧰 **Error Handling** on both **client** and **server**
- 📦 **Image Upload** with Cloudinary
- 📁 **Clean Code Structure** for scalability
- 🌐 **Ready for Deployment**

---

## 🛠️ Environment Variables

Create a `.env` file in the root of the **backend** with the following keys:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret_key

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development
```
---
## 📦 Installation

# Clone the repository
git clone https://github.com/nipamrohit/ChatApp.git
cd ChatApp

# Install Backend Dependencies
cd backend
npm install

# Install Frontend Dependencies
cd ../frontend
npm install

---

## 🧪 Development
# Start Backend Server
cd backend
npm run dev

# Start Frontend Server
cd frontend
npm run dev

---

## 🏗️ Build for Production

# From frontend directory
npm run build

---

## 📁 Folder Structure
ChatApp/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── lib/
│   └── ...
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   ├── state/
│   └── ...
