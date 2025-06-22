# Event Management System

This web application allows users to browse and register for events, while administrators can create and manage events. Built with React frontend and Node.js backend using MongoDB.

## 🛠 Prerequisites

1. [Visual Studio Code](https://code.visualstudio.com/download) (latest version)  
2. [Node.js v18+](https://nodejs.org) (includes npm)  
3. [MongoDB Community Server](https://www.mongodb.com/try/download/community)  
4. [Git](https://git-scm.com/downloads) (optional for cloning)  

## 📥 Installation

1. **Download/extract project files** to `C:\Event-Management-System-main`  
2. **Open VS Code** and launch Terminal (Ctrl + \`)  
3. **Install backend dependencies**:
   ```bash
   cd C:\Event-Management-System-main\backend
   npm install
   ```
4. **Install frontend dependencies**:
   ```bash
   cd C:\Event-Management-System-main\frontend
   npm install
   ```

## 🚀 Running the Application

**Start Backend Server**
```bash
cd C:\Event-Management-System-main\backend
npm start
```

**Expected Output:**
```
[nodemon] starting `node index.js`
Server started at 4000
Connected to DB
```

**Start Frontend Server**
```bash
cd C:\Event-Management-System-main\frontend
npm start
```

**Expected Output:**
```
Compiled successfully!
Local:            http://localhost:3000
On Your Network:  http://192.168.56.1:3000
```

Automatically opens browser at [http://localhost:3000](http://localhost:3000)

## 👥 User Features

- **Authentication:** Sign up and login  
- **Event Browsing:** View all available events  
- **Event Details:** See event descriptions, dates, and locations  
- **Registration:** Sign up for events  
- **Dashboard:** View registered events  

## 👨‍💼 Admin Features

- **Admin Login:** Special admin credentials  
- **Event Management:** Add, edit, and delete events  
- **Attendee Tracking:** View registered users for each event  
- **Event Configuration:** Manage event parameters and settings  
