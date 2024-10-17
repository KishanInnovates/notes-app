# Notes App
A simple and intuitive Notes App built with React for the frontend and Node.js for the backend. This app allows users to create, edit, delete, pin, and search notes easily.

# Live Demo
https://notes-app-nu-pied.vercel.app/login

# ✨ Features
-📝 Add Note: Create new notes quickly and easily. 
- ✏️ Edit Note: Update any note with new information.
- ❌ Delete Note: Remove notes that are no longer needed.
- 📌 Pin Note: Pin important notes to the top of your list.
- 🔍 Search Note: Find specific notes with the built-in search functionality.

# 🛠️ Tech Stack
- Frontend: React, Tailwind CSS
- Backend: Node.js, Express.js
- Database: MongoDB Atlas

# Getting Started
## Prerequisites
- Ensure you have Node.js and MongoDB installed locally, or use MongoDB Atlas for cloud database hosting.

## 💻 How to Run the Project
- Clone this repository to your local machine:
```
git clone https://github.com/KishanInnovates/notes-app.git

```
- Navigate to the project directory:
```
cd notes-app
```
- Install dependencies for both frontend and backend:
```
cd frontend
npm install
cd ../backend
npm install
```
- Set up environment variables for the backend:
- Create a .env file in the backend/ folder.
- Add your MongoDB URI and secret for JWT:
```
MONGODB_URI=<your-mongo-uri>
ACCESS_TOKEN_SECRET=<your-secret>
```
- Run the app:
- In frontend/:
```
npm run dev
```
- In backend/:
```
node index.js
```

# Feedback
Feel free to provide feedback by raising an issue on the GitHub repository and also Star the repo.
