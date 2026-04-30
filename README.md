# 🍽️✨ FOODIO — Social Media for Food Lovers

FOODIO is an aesthetic MERN-based social media platform designed for people who enjoy sharing food experiences.  
A warm, expressive space where posts, pictures, and culinary memories come together in a beautiful interface.


# 🥗 What is FOODIO?

FOODIO is a **visual social platform** where users can upload food posts, follow creators, like posts, comment, and explore food content from around the world.

It focuses on:
- Aesthetic user experience  
- Smooth UI interactions  
- Simple and intuitive design  
- Social engagement with food-centric content  

> “Food connects us — FOODIO makes that connection visual, social, and meaningful.”

# 🌟 Highlights

- 📸 Upload food posts  
- ❤️ Like & 💬 comment on posts  
- 👥 Follow other users  
- 👤 Customizable profile  
- 📰 Personalized home feed  
- 🔐 JWT authentication  
- 🎨 Minimal & aesthetic UI  
- ⚡ Fast MERN stack performance  

---

# 🎨 Aesthetic Vision

FOODIO aims to feel like a **soft, warm food community** with:

🌸 Calm gradients  
📱 Modern card layouts  
🧁 Soft UI patterns  
🍃 Clean typography  

---

# 🔥 Core Features

### ✨ User Features
- Post photos and captions  
- Like & unlike posts  
- Add/view comments  
- Explore feed  
- Follow other users  
- View profiles  
- Edit profile  
- Secure login & signup  

---

# 🧩 Tech Stack

### 🎨 Frontend
- React.js  
- React Router  
- Tailwind / CSS  
- Axios  

### 🔧 Backend
- Node.js  
- Express.js  
- MongoDB  
- Mongoose  
- JWT  
- bcrypt.js  

---

# 🛠️ Installation & Setup

### 👉 Clone Repository
git clone https://github.com/xNikhilx1/FOODIO.git
cd FOODIO

👉 Install Backend Dependencies
cd backend
npm install

👉 Install Frontend Dependencies
cd ../frontend
npm install

👉 Environment Variables

Create a file named .env inside backend folder and add:

MONGO_URI=your_connection_string
JWT_SECRET=your_secret_key
PORT=5000

🚀 Run the Project
👉 Start Backend
cd backend
npm start

👉 Start Frontend
cd frontend
npm run dev


Your project will run on:

Frontend: http://localhost:5173

Backend: http://localhost:5000

📡 API Overview
🔐 Authentication
POST /api/auth/register
POST /api/auth/login

📸 Posts
POST /api/posts
GET /api/posts
DELETE /api/posts/:id

❤️ Likes
POST /api/posts/:id/like

💬 Comments
POST /api/posts/:id/comment

📂 Folder Structure
FOODIO/
│── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── hooks/
│   │   └── utils/
│   └── public/
│
│── backend/
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   └── config/
│
└── README.md


MongoDB Not Connecting
Check MONGO_URI

Verify IP whitelist on MongoDB Atlas

Port Already in Use
bash
Copy code
npx kill-port 5173
npx kill-port 5000
JWT Errors
Ensure the token is included in headers

Confirm JWT_SECRET is correct

✨ Author
Nikhil G
GitHub: xNikhilx1
---

If you want:

✨ Add color dividers  
✨ Add gradient backgrounds  
✨ Add badges (tech badges, star badges, etc.)  
✨ Add an ASCII banner  
✨ Make it EVEN more aesthetic

