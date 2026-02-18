

🚀 Talent IQ – Full-Stack Interview Platform
<p align="center"> <img src="https://img.shields.io/badge/MERN-Stack-3FA037?style=for-the-badge&logo=mongodb&logoColor=white" /> <img src="https://img.shields.io/badge/React-19-61DAFB?style=for-the-badge&logo=react&logoColor=black" /> <img src="https://img.shields.io/badge/Node.js-Backend-339933?style=for-the-badge&logo=node.js&logoColor=white" /> <img src="https://img.shields.io/badge/Express.js-API-000000?style=for-the-badge&logo=express&logoColor=white" /> <img src="https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white" /> </p> <p align="center"> <b>A powerful real-time interview practice platform with live video calls, collaborative coding, and AI-powered feedback.</b> </p>
🌟 Overview

Talent IQ is a production-ready MERN Stack interview simulator designed to replicate real-world technical interviews.

It enables:

🎥 Live 1-on-1 interviews
🧑‍💻 Real-time collaborative coding
⚡ Instant code execution
📊 Performance tracking dashboard
🔐 Secure authentication
🎯 Built to simulate FAANG-style coding interviews with scalable architecture.
🧠 Why Talent IQ?

✔ Real-time collaboration
✔ Interview-grade coding environment
✔ Multi-language execution engine
✔ Production-ready authentication
✔ Scalable backend architecture

✨ Key Features
Feature	Description
🧑‍💻 Collaborative Code Editor	VS Code-like Monaco editor with JS / Python / Java
🎥 1-on-1 Video Rooms	Screen sharing, mic/camera toggle & recording
💬 Live Chat	Real-time messaging during sessions
🔐 Authentication	Clerk (Email, Google, GitHub login)
🧠 Practice Problems	Structured DSA challenges with test cases
⚙️ Code Execution	Secure execution via Piston API
🎯 Auto Feedback	Pass/Fail detection + Confetti celebration 🎉
🔒 Room Locking	Only 2 participants allowed per room
📊 Dashboard	Track stats, solved problems & session history
🚀 Background Jobs	Async workflows powered by Inngest
🧰 Tech Stack
💻 Frontend
<p> <img src="https://skillicons.dev/icons?i=react,vite,tailwind,typescript" /> </p>

React 19

Vite

Tailwind CSS

Clerk Authentication

Stream Video SDK

🖥 Backend
<p> <img src="https://skillicons.dev/icons?i=nodejs,express,mongodb" /> </p>

Node.js

Express.js

MongoDB

Inngest

⚙️ Third-Party Services

⚡ Piston API – Code execution engine

🔐 Clerk – Authentication & session management

🎥 Stream – Video SDK

📂 Project Structure
talent-iq/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── server.js
│
├── frontend/
│   ├── components/
│   ├── pages/
│   └── main.jsx
│
└── README.md

🚀 Getting Started
📌 Prerequisites

Node.js v18+

MongoDB (Local / Atlas)

Git

🔧 Installation
git clone https://github.com/yourusername/talent-iq.git
cd talent-iq

npm install --prefix backend
npm install --prefix frontend

🔑 Environment Variables
Backend (backend/.env)
PORT=3000
NODE_ENV=development
DB_URL=mongodb://localhost:27017/talent-iq

INNGEST_EVENT_KEY=your_key
INNGEST_SIGNING_KEY=your_key

STREAM_API_KEY=your_key
STREAM_API_SECRET=your_secret

CLERK_PUBLISHABLE_KEY=your_key
CLERK_SECRET_KEY=your_secret

CLIENT_URL=http://localhost:5173

Frontend (frontend/.env)
VITE_CLERK_PUBLISHABLE_KEY=your_key
VITE_API_URL=http://localhost:3000/api
VITE_STREAM_API_KEY=your_key

🏃 Run the Application
Backend
cd backend
npm run dev

Frontend
cd frontend
npm run dev


Or run both:

npm run dev

🌐 Application URLs
Service	URL
Frontend	http://localhost:5173

Backend	http://localhost:3000

Health Check	http://localhost:3000/health
🌍 Deployment
Backend (Render / Railway / Sevalla)

Add environment variables

Build: npm install

Start: npm start

Frontend (Vercel / Netlify)

Add VITE_* variables

Build: npm run build

Deploy dist/

📊 Architecture Overview
User → React Frontend → Express API → MongoDB
                     ↓
                 Piston API (Execution)
                     ↓
                 Stream (Video)
                     ↓
                 Clerk (Auth)

🧪 Testing

Currently no automated tests implemented.
Contributions are welcome!

🤝 Contributing

Fork the repository

Create a new branch

Commit your changes

Push and open a Pull Request

📌 Future Improvements

🤖 AI-powered interview analysis

🧠 Plagiarism detection

🎥 Interview playback system

🏆 Global leaderboard

📈 Admin analytics dashboard

📜 License

MIT License

👨‍💻 Author
Rishabh Sahu

Full-Stack Developer | MERN Stack Engineer | AI Enthusiast

⭐ If you like this project

Give it a ⭐ on GitHub and support the development!
