# ChatNest - Real-Time Chat Application

ChatNest is a **real-time chat application** built using the **MERN stack**, **Zustand** for state management, **DaisyUI** and **Tailwind CSS** for UI, and **Socket.io** for real-time communication.


## 🚀 Features

- 🔐 **JWT Authentication** (Sign Up & Login)
- 🟢 **Real-Time Messaging** with **Socket.io**
- 👥 **Group & Private Chats**
- 🌙 **Dark & Light Mode** (DaisyUI Themes)
- 📄 **Beautiful UI** with **DaisyUI & Tailwind CSS**
- 📌 **User Status Indicator** (Online/Offline)
- 🔄 **Optimized State Management** with **Zustand**
- 📂 **Media & File Sharing** (Planned)
- ⚡ **WebSocket-Based Instant Communication**

## 🛠 Tech Stack

### **Frontend**
- React.js (Vite)
- Zustand (State Management)
- DaisyUI & Tailwind CSS (Styling)
- Axios (API Requests)

### **Backend**
- Node.js & Express.js
- MongoDB (Mongoose ODM)
- JWT Authentication
- Socket.io (WebSockets for real-time chat)

## ⚡ Setup & Installation

### 1️⃣ Clone the Repository
```bash
 git clone https://github.com/yourusername/chatnest.git
 cd chatnest
```

### 2️⃣ Install Dependencies
```bash
# Install frontend dependencies
cd client
npm install

# Install backend dependencies
cd ../server
npm install
```

### 3️⃣ Configure Environment Variables
Create a `.env` file in the **server** directory and add:
```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
CLIENT_URL=http://localhost:5173
```

### 4️⃣ Start the Application
```bash
# Start backend server
cd server
npm start

# Start frontend client
cd client
npm run dev
```

## 🎨 UI Preview
![ChatNest UI](#) <!-- Add a screenshot link here -->

## 🤝 Contribution
Feel free to fork and contribute! Submit a PR with your improvements. 🚀

## 📜 License
This project is licensed under the MIT License.

## 📬 Contact
For any queries, reach out at **your-email@example.com** or connect on [LinkedIn](#).

Happy Coding! 🎉

