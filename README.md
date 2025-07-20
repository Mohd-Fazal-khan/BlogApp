# 📝 Blogify - MERN Stack Blog App  
A full-stack web application for creating and managing blogs, built with React, Node.js, Express, and MongoDB.

## ✨ Features

- 🧾 Blog Post Management: Create, update, delete blog posts with cover image support
- 🔐 Authentication: Secure login and registration with JWT
- 📝 Rich Text Editor: Write posts with formatting (Markdown or WYSIWYG)
- 🔍 Blog Search: Find posts by title or author
- 👤 User Profiles: See all posts from a particular author
- 📱 Responsive UI: Fully mobile-friendly interface

---

## 🛠 Tech Stack

### Frontend
- React with Vite
- React Router
- Axios
- TailwindCSS
- Toast notifications (e.g., React Toastify)
- Rich Text Editor (e.g., React Quill)

### Backend
- Node.js & Express
- MongoDB & Mongoose
- JWT for authentication
- Multer or Cloudinary for image uploads
- CORS enabled

---

## 🚀 Getting Started

### 📦 Prerequisites
- Node.js
- MongoDB Atlas
- Cloudinary account (if using for image hosting)

---

### Installation

1. Clone the repository
```bash
git clone https://github.com/Mohd-Fazal-khan/BlogApp
1) Backend
cd backend
npm install

Crete .env file and add
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret


2) Frontend
cd frontend
npm install

Crete .env file and add
VITE_API_URL=http://localhost:5000
```
### Run your Project
1) Frontend
   
   npm run dev
3) Backend
   
   npm run dev
