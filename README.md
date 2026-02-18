🚀 Talent IQ – Full-Stack Interview Intelligence Platform

A modern, production-ready technical interview simulation platform built with the MERN stack.
Talent IQ replicates real-world FAANG-style coding interviews with live video rooms, collaborative coding, and intelligent feedback systems.

🎯 Vision

Talent IQ aims to bridge the gap between coding practice and real interview environments by providing:

Real-time collaborative coding

Live 1-on-1 video interviews

Structured DSA practice system

Automated evaluation engine

Scalable backend architecture

✨ Core Features
🧑‍💻 Collaborative Coding Environment

Monaco Editor (VS Code-like experience)

Multi-language support (JavaScript, Python, Java)

Real-time collaboration

Syntax highlighting & formatting

Integrated execution system

🎥 Live Interview Rooms

1-on-1 secure video sessions

Screen sharing support

Mic / Camera toggle

Session recording

Room locking (max 2 participants)

💬 Real-Time Chat

In-room instant messaging

Seamless communication during interviews

⚙️ Code Execution Engine

Secure sandbox execution via Piston API

Multi-language support

Custom test case validation

Output comparison logic

🎯 Automated Feedback System

Pass/Fail detection

Test case validation

Visual celebration (Confetti 🎉)

Performance tracking

📊 Interview Dashboard

Session history

Problems solved

Performance analytics

Interview statistics

🔐 Authentication & Security

Clerk authentication (Email / Google / GitHub)

Session-based authentication

Protected routes

Role-based access (extendable)

🚀 Background Processing

Inngest-powered async workflows

Scalable job processing

Event-driven architecture

🧠 Technical Highlights

Real-time collaborative editor integration

Video SDK integration with Stream

Secure execution environment

Event-driven backend architecture

Modular scalable project structure

RESTful API design

MongoDB document modeling with Mongoose

🛠 Tech Stack
💻 Frontend

React 19

Vite

Tailwind CSS

TypeScript (optional)

Clerk Authentication

Stream Video SDK

Monaco Editor

🖥 Backend

Node.js

Express.js

MongoDB

Mongoose ODM

Inngest

⚙️ Third-Party Services

Piston API – Secure code execution

Clerk – Authentication & user management

Stream – Real-time video SDK

Inngest – Background job orchestration

📁 Project Structure
talent-iq/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   └── server.js
│
├── frontend/
│   ├── components/
│   ├── pages/
│   ├── hooks/
│   └── main.jsx
│
└── README.md

🔑 Environment Configuration
Backend (.env)
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

Frontend (.env)
VITE_CLERK_PUBLISHABLE_KEY=your_key
VITE_API_URL=http://localhost:3000/api
VITE_STREAM_API_KEY=your_key

🚀 Getting Started
📌 Prerequisites

Node.js v18+

MongoDB (Local or Atlas)

Git

🔧 Installation
git clone https://github.com/yourusername/talent-iq.git
cd talent-iq

npm install --prefix backend
npm install --prefix frontend

🏃 Development Mode
Backend
cd backend
npm run dev

Frontend
cd frontend
npm run dev


Or run both:

npm run dev

🌐 Local URLs

Frontend → http://localhost:5173

Backend → http://localhost:3000

Health Check → http://localhost:3000/health

📊 System Architecture
User
  ↓
React Frontend (Vite)
  ↓
Express API Server
  ↓
MongoDB Database
  ↓
External Services:
   ├── Piston (Code Execution)
   ├── Stream (Video)
   ├── Clerk (Auth)
   └── Inngest (Background Jobs)

🔒 Security Considerations

Auth-protected API routes

Secure environment variables

Input validation

Execution sandbox isolation

Room participant limit enforcement

🌍 Deployment Guide
Backend (Render / Railway / Sevalla)

Add environment variables

Build: npm install

Start: npm start

Frontend (Vercel / Netlify)

Add VITE_* environment variables

Build: npm run build

Deploy dist/ folder

🧪 Testing

No automated tests implemented yet.
Contributions are welcome for:

Unit tests

API integration tests

E2E testing

🚀 Future Roadmap

🤖 AI-powered interview evaluation

🧠 Plagiarism detection

🎥 Interview playback system

🏆 Global leaderboard

📈 Admin analytics dashboard

🌎 Multi-room interview system

📊 Advanced performance insights

🤝 Contributing

Fork the repository

Create a feature branch

Commit your changes

Open a Pull Request

📜 License

MIT License

👨‍💻 Author

Rishabh Sahu
Full-Stack Developer | MERN Stack Engineer | AI Enthusiast
