<!-- 📌 MiniSlack – Real-Time Team Communication App

MiniSlack is a lightweight, full-stack messaging application inspired by Slack. It allows users to create channels, send and receive messages in real-time, and manage their workspace efficiently.
Built using React (frontend), Node.js + Express (backend), and MongoDB (database).

🚀 Features
✅ Channel Management

Create channels

Select active channels

View all channels

💬 Real-Time Messaging

Send and receive messages instantly

Auto-refresh message list

Backend message routing via Express APIs

📡 REST API Integration

Fully functional backend

Axios-based frontend API calls

Error-handling at both ends

📂 Persistent Storage

MongoDB stores channels and messages

Mongoose models for structured data

🎨 Modern Frontend

Built using React + Vite

Clean UI for smooth chat experience

🛠️ Tech Stack
Frontend

React

Vite

Axios

TypeScript (optional in components)

Backend

Node.js

Express.js

MongoDB

Mongoose

Tools

Postman

VS Code

Git/GitHub

📁 Project Structure
MiniSlack/
│
├── backend/
│   ├── server.js
│   ├── routes/
│   │   ├── channelRoutes.js
│   │   ├── messageRoutes.js
│   ├── models/
│   │   ├── Channel.js
│   │   ├── Message.js
│   └── config/
│       └── db.js
│
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── ChannelList.tsx
│   │   │   ├── ChatWindow.tsx
│   │   │   ├── MessageInput.tsx
│   │   └── App.tsx
│   └── vite.config.js
│
└── README.md

⚙️ Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourname/minislack
cd minislack

🖥️ Backend Setup
2️⃣ Install backend dependencies
cd backend
npm install

3️⃣ Set up environment variables

Create a .env file:

MONGO_URI=your_mongodb_connection_string
PORT=5000

4️⃣ Start backend
npm start


or

nodemon server.js

🎨 Frontend Setup
5️⃣ Install React dependencies
cd ../frontend
npm install

6️⃣ Start frontend
npm run dev

🔗 API Endpoints
Channels
Method	Endpoint	Description
GET	/api/channels	Get all channels
POST	/api/channels	Create a new channel
Messages
Method	Endpoint	Description
GET	/api/messages/:channelId	Get messages of a channel
POST	/api/messages	Create a new message
📸 Screenshots (add when available)

Place screenshots inside:

/frontend/public/screenshots/


Then reference like:

![Chat UI](public/screenshots/chat.png)

🚀 Deployment Guide
Frontend

Deploy using:

Netlify

Vercel

GitHub Pages

Backend

Deploy using:

Render

Railway

Vercel Serverless

AWS EC2

Make sure to:

Add your MongoDB URI

Update frontend axios base URL to deployed backend URL

👩‍💻 Contributing

Fork project

Create a feature branch

Commit changes

Push to branch

Open a PR

📜 License

This project is licensed under the MIT License. -->