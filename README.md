# ✨ Full Stack Realtime Chat App ✨

<p align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  <img src="https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Socket.io-010101?style=for-the-badge&logo=socket.io&logoColor=white" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
  <img src="https://img.shields.io/badge/DaisyUI-FF69B4?style=for-the-badge&logo=daisyui&logoColor=white" />
  <img src="https://img.shields.io/github/license/nipamrohit/ChatApp?style=for-the-badge" />
</p>

---

<p align="center">
  <b>A feature-rich, modern, and scalable real-time chat application built with the MERN stack, Socket.io, Tailwind CSS, and DaisyUI.</b>
</p>

---

## 🚀 Demo

<p align="center">
  <img src="https://github.com/nipamrohit/ChatApp/raw/main/demo.gif" alt="Chat App Demo" width="700"/>
</p>

> **Note:** Replace the above image with your own GIF or screenshot for a live demo!

---

## 📑 Table of Contents

- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Environment Variables](#-environment-variables)
- [Usage](#-usage)
- [Folder Structure](#-folder-structure)
- [Contributing](#-contributing)
- [License](#-license)
- [Credits](#-credits)

---

## ✨ Features

- 🔐 **Authentication & Authorization** (JWT-based)
- 💬 **Real-time Messaging** (Socket.io)
- 🟢 **Online User Presence**
- 🌍 **Global State Management** (Zustand)
- 🧰 **Robust Error Handling** (Client & Server)
- 📦 **Image Uploads** (Cloudinary)
- 📁 **Clean, Scalable Code Structure**
- 🌐 **Production Ready**
- 🎨 **Modern UI** (Tailwind CSS + DaisyUI)
- 📱 **Responsive Design**
- 🛡️ **Secure API Endpoints**

---

## 🛠️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,react,mongodb,tailwind,js,ts,cloudinary,vercel" />
</p>

- **Frontend:** React, Zustand, Tailwind CSS, DaisyUI
- **Backend:** Node.js, Express, MongoDB, Socket.io
- **Cloud:** Cloudinary (Image Uploads)
- **Deployment:** Vercel/Render/Heroku (your choice)

---

## 🏁 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/nipamrohit/ChatApp.git
cd ChatApp
```

### 2. Install Dependencies

#### Backend
```bash
cd backend
npm install
```

#### Frontend
```bash
cd ../frontend
npm install
```

---

## 🔑 Environment Variables

Create a `.env` file in the `backend/` directory with the following:

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

## ▶️ Usage

### Start Backend Server
```bash
cd backend
npm run dev
```

### Start Frontend Server
```bash
cd frontend
npm run dev
```

### Build for Production
```bash
# From frontend directory
npm run build
```

---

## 📁 Folder Structure

```
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
```

---

## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

1. Fork the repo
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙏 Credits

- [Nipam Rohit](https://github.com/nipamrohit) - Original Author
- [Socket.io](https://socket.io/), [MongoDB](https://www.mongodb.com/), [Cloudinary](https://cloudinary.com/), [Tailwind CSS](https://tailwindcss.com/), [DaisyUI](https://daisyui.com/)

---

<p align="center">
  <b>⭐️ If you like this project, give it a star on GitHub! ⭐️</b>
</p>
