# ✅ Fullstack To-Do App 
A fully functional fullstack To-Do web application built using the MERN stack (MongoDB, Express.js, React, Node.js). This app allows users to register, log in, and manage their personal to-do lists with a simple and intuitive interface.

---

## 📌 Features

- User authentication (Register/Login/Logout)
- JWT-based secure sessions
- Create, update, delete to-do items
- Responsive and clean UI
- Modular code structure

---

## 🛠️ Tech Stack

**Frontend:**
- React.js
- CSS Modules
- Axios

**Backend:**
- Node.js
- Express.js
- MongoDB (via Mongoose)
- JWT for authentication
- bcryptjs for password hashing

---

## 📁 Project Structure

todo-app/
├── client/ # React frontend
├── controllers/ # Backend logic for auth and todo
├── middleware/ # JWT authentication middleware
├── models/ # Mongoose models for User and ToDo
├── routes/ # Express API routes
├── server.js # Entry point for backend
├── package.json # Backend dependencies

yaml
Copy
Edit

---

## 🚀 Getting Started

### Prerequisites
- Node.js and npm
- MongoDB installed or use [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

### 1. Clone the repository

```bash
git clone https://github.com/your-username/krishnaa-koushik-todo-app.git
cd krishnaa-koushik-todo-app
2. Setup Backend
bash
Copy
Edit
npm install
# Create a .env file and add your MongoDB URI and JWT_SECRET
node server.js
3. Setup Frontend
bash
Copy
Edit
cd client
npm install
npm start
The app will be available at http://localhost:3000.

🧪 Folder Breakdown – Frontend (client/)
components/ – Common reusable components (e.g., Navbar)

pages/ – Page-level components (Auth, Landing, ToDo)

services/ – Axios service files for API interaction

util/ – Helper utilities for error handling and user state

🔒 Security Notes
JWT tokens are stored securely and used for protected routes.

Passwords are hashed using bcrypt before being stored in MongoDB.

✨ Future Improvements
Add due dates and reminders for to-dos

Profile management

Priority tagging

Dark mode support

👤 Author
Battaram Krishnaa Koushik
Fullstack Developer | CSE @ VIT-AP
Email: battaramkrishnakoushik123@gmail.com

📃 License
This project is for academic use only.



