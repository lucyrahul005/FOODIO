# 🍽️ FOODIO – AI Powered Recipe Platform

## 🚀 Overview

FOODIO is a full-stack web application that helps users discover, create, and manage recipes with the power of AI.
It combines modern UI/UX with intelligent features like AI-based recipe generation and a chatbot assistant.

---

## ✨ Features

* 🔐 User Authentication (JWT-based login/signup)
* 🤖 AI Recipe Generator
* 💬 Chatbot Integration
* 📚 Browse & Filter Recipes
* ❤️ Save / Favorite Recipes
* 📝 Add & Manage Your Own Recipes
* 🌗 Light/Dark Theme Support
* 📱 Fully Responsive Design

---

## 🛠️ Tech Stack

### Frontend

* React.js (Vite)
* Tailwind CSS
* Context API

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)

### Other Tools

* JWT Authentication
* REST APIs
* Git & GitHub

---

## 🧠 Architecture (High-Level)

* Frontend communicates with backend via REST APIs
* Backend handles authentication, business logic, and database operations
* MongoDB stores users, recipes, and related data
* AI module processes user input to generate recipes

---

## 📂 Project Structure

```
FOODIO/
│
├── frontend/        # React application
├── backend/         # Node + Express server
├── controllers/     # Business logic
├── models/          # Database schemas
├── routes/          # API routes
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repo

```
git clone https://github.com/your-username/foodio.git
cd foodio
```

### 2️⃣ Install dependencies

```
cd backend
npm install

cd ../frontend
npm install
```

### 3️⃣ Run the app

```
# backend
npm start

# frontend
npm run dev
```

---

## 🔐 Environment Variables

Create a `.env` file in backend:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

---

## 📸 Screenshots

(Add your images here – you already have them in public folder)

---

## 🎯 Key Highlights (For Interviewers)

* Designed a scalable full-stack architecture
* Implemented secure authentication using JWT
* Built reusable React components using Context API
* Integrated AI-based feature for dynamic content generation
* Optimized API calls and state management

---

## 🚧 Future Improvements

* 🧠 Better AI recommendations
* 📊 Analytics dashboard
* 🌍 Multi-language support
* 📱 Mobile app version

---

## 🙋‍♂️ Author

**Rahul Vardhanapu**

* GitHub: https://github.com/your-username
* LinkedIn: (add your link)

---

## ⭐ If you like this project

Give it a star ⭐ on GitHub!
