# 🎉 Event Management System

A full-stack web application that allows users to browse and register for events. Administrators can manage and monitor events. Built with a simple HTML/CSS/JS frontend and Node.js/Express backend with MongoDB.

---

## 🛠 Prerequisites

Make sure the following tools are installed on your system:

1. [Visual Studio Code](https://code.visualstudio.com/download)  
2. [Node.js v18+](https://nodejs.org) (includes npm)  
3. [MongoDB Community Server](https://www.mongodb.com/try/download/community)  
4. [Git](https://git-scm.com/downloads) (optional, for version control)  

---

## 📁 Project Structure

```
Event-Management-System-main/
│
├── backend/
│   ├── controller/          # Backend logic and route handlers
│   ├── model/               # Mongoose models for MongoDB
│   ├── index.js             # Entry point of backend server
│   ├── package.json         # Backend dependencies
│   └── package-lock.json
│
├── frontend/
│   ├── public/              # Static assets (if any)
│   ├── src/                 # Source scripts/styles (if any)
│   ├── Register.html        # Registration page
│   ├── events.html          # Events listing page
│   ├── package.json         # Frontend (optional use)
│   ├── package-lock.json
│   └── .gitignore
│
├── README.md
├── package.json             # Root-level (if monorepo setup)
└── package-lock.json
```

---

## 📥 Installation Steps

1. **Extract or clone** the project to `C:\Event-Management-System-main`  
2. Open the folder in **Visual Studio Code**  
3. Open Terminal (press `Ctrl + \``)

### 🔧 Install backend dependencies:
```bash
cd C:\Event-Management-System-main\backend
npm install
```

### 🔧 (Optional) Install frontend dependencies if any:
```bash
cd C:\Event-Management-System-main\frontend
npm install
```

---

## 🚀 Run the Application

### ✅ Start Backend Server
```bash
cd C:\Event-Management-System-main\backend
npm start
```
Expected Output:
```
[nodemon] starting `node index.js`
Server started at 4000
Connected to DB
```

### 🌐 Open Frontend

Simply open the following files in your browser:

- `frontend/Register.html` — to register for events  
- `frontend/events.html` — to view events  

You can also serve them using a live server extension in VS Code.

---

## 🔐 Environment Variables

Create a `.env` file inside the `backend` directory with the following:

```
PORT=4000
MONGODB_URI=mongodb://localhost:27017/eventdb
JWT_SECRET=your_secret_key
```

---

## 👥 User Features

- 🔐 User Authentication (Sign up/Login)  
- 📅 View all events  
- 📖 Event details (title, date, location, description)  
- 📝 Register for events  
- 📋 Dashboard to view registered events  

---

## 👨‍💼 Admin Features

- 🔐 Admin Login  
- ➕ Add new events  
- ✏️ Edit existing events  
- ❌ Delete events  
- 👥 View attendees for each event  

---

## 🧰 Tech Stack

| Layer        | Technology             |
|--------------|------------------------|
| Frontend     | HTML, CSS, JavaScript  |
| Backend      | Node.js, Express.js    |
| Database     | MongoDB with Mongoose  |
| Auth         | JWT, bcrypt            |

---

## 🤝 Contributing

1. Fork the repository  
2. Create a new branch: `git checkout -b feature/your-feature`  
3. Commit your changes: `git commit -am 'Add new feature'`  
4. Push to the branch: `git push origin feature/your-feature`  
5. Open a pull request  

---

## 📧 Contact

For suggestions or queries, email: **chethankaregowda@gmail.com**

---

## 📜 License

This project is licensed under the **MIT License**.
