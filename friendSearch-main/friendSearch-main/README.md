# 📚 friendSearch – Find Your Ideal Study Partner

**friendSearch** is a full-stack MERN-based application that helps students connect with compatible study buddies through a swipe-based interface — like Tinder, but for academic collaboration. With real-time chat, animated UI, and instant notifications, learning becomes social and fun.

---

## 🚀 Live Demo

🌐 [Try It Live](https://studysync-1-thil.onrender.com/auth)  
🧑‍💻 [GitHub Repository](https://github.com/sudritghimire-ai/friendSearch)

---

## 🎯 Features

- 🔄 "Swipe Interface" – Match with study partners using a Tinder-style card system  
- 💬 "Real-time Messaging" – Instantly chat with matches via Socket.io  
- 🔔 "Instant Notifications" – Toast alerts for new matches or messages  
- 🧠 "Smart Matching" – Suggests users based on study interests and availability  
- 📱 "Mobile-Responsive" – Fully responsive UI using Tailwind CSS  
- 🎨 "Animated Visuals" – Background animation with Lottie and Framer Motion

---

## 🛠️ Tech Stack

| Layer      | Technologies                             |
|------------|------------------------------------------|
| Frontend   | React, Tailwind CSS, Zustand, Toastify   |
| Backend    | Node.js, Express.js, MongoDB, Mongoose   |
| Real-time  | Socket.io                                |
| Auth       | JWT (JSON Web Token)                     |
| Hosting    | Render (Full-stack deployment)           |

---

## 📁 Folder Structure

"friendSearch/"
├── "api/"               → Express backend  
│   ├── "config/"        → MongoDB & Cloudinary config  
│   ├── "controllers/"   → API logic  
│   ├── "models/"        → Mongoose schemas  
│   └── "routes/"        → API endpoints  
│  
├── "client/"            → React frontend  
│   ├── "components/"    → Reusable UI elements  
│   ├── "pages/"         → Route pages (Chat, Auth, Home)  
│   └── "store/"         → Zustand state management  
│  
├── ".env"               → Environment variables  
├── "package.json"       → Project metadata and scripts  
├── "yarn.lock"          → Dependency lock file  

---

## ⚙️ Setup & Installation

### 1. Clone the Repo

"git clone https://github.com/sudritghimire-ai/friendSearch.git"  
"cd friendSearch"

### 2. Install Dependencies

"npm install"  
"cd client && npm install"

### 3. Configure Environment Variables

Create a ".env" file in the root directory with the following keys:

"PORT=5000"  
"MONGO_URI=your_mongodb_connection_string"  
"JWT_SECRET=your_secret_key"  
"CLOUDINARY_NAME=your_cloud_name"  
"CLOUDINARY_KEY=your_api_key"  
"CLOUDINARY_SECRET=your_api_secret"

---

## 📸 Screenshots

| Swipe Page                                    | Chat Page                                    |
|----------------------------------------------|----------------------------------------------|
| ![Swipe](https://via.placeholder.com/300x200) | ![Chat](https://via.placeholder.com/300x200) |

---

## 📜 License

MIT © [Sudrit Ghimire](https://github.com/sudritghimire-ai)

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
