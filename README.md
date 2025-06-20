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

📦 Installation
Clone the repo
bash
Copy
Edit
git clone https://github.com/nipamrohit/ChatApp.git
cd ChatApp
Install dependencies for both frontend & backend
bash
Copy
Edit
# Backend
cd backend
npm install

# Frontend
cd ../frontend
npm install
🧪 Development
Start Backend
bash
Copy
Edit
cd backend
npm run dev
Start Frontend
bash
Copy
Edit
cd frontend
npm run dev
🏗️ Build for Production
bash
Copy
Edit
# From frontend directory
npm run build
📸 Screenshot


📁 Folder Structure
Copy
Edit
ChatApp/
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── ...
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── assets/
│   └── ...
📃 License
This project is licensed under the MIT License.