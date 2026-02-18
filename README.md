🎯 Talent IQ – Full-Stack Interview Platform
<p align="center"> <img src="https://img.shields.io/badge/MERN-Stack-green?style=for-the-badge" /> <img src="https://img.shields.io/badge/TypeScript-optional-blue?style=for-the-badge" /> <img src="https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge" /> </p><p align="center"> A complete interview practice platform with **real-time video calls**, **collaborative code editor**, and **AI‑powered feedback**. </p>
✨ Highlights
Feature	Description
🧑‍💻 Code Editor	VS Code‑like Monaco editor with multi‑language support (JS/Python/Java)
🔐 Authentication	Secure login via Clerk (email, Google, GitHub)
🎥 Video Interviews	1‑on‑1 video rooms with screen sharing, mic/camera toggle, recording
💬 Live Chat	Real‑time messaging during sessions
🧠 Practice Problems	Curated list of coding challenges with test cases
🎯 Auto Feedback	Success/failure based on output; confetti on pass 🎉
🔒 Room Locking	Only two participants per session
⚙️ Code Execution	Isolated execution via Piston API
🧰 Dashboard	Track sessions, problems solved, stats
🚀 Background Jobs	Async tasks handled by Inngest
🛠️ Tech Stack
<div align="center">
Frontend	Backend	Database	Services
<img src="https://img.icons8.com/color/48/000000/react-native.png" width="40"/> React 19	<img src="https://img.icons8.com/color/48/000000/nodejs.png" width="40"/> Node.js	<img src="https://img.icons8.com/color/48/000000/mongodb.png" width="40"/> MongoDB	<img src="https://cdn.jsdelivr.net/gh/alohe/emojipedia/custom-emoji/clerk.svg" width="40"/> Clerk
<img src="https://img.icons8.com/color/48/000000/typescript.png" width="40"/> TypeScript (optional)	<img src="https://img.icons8.com/color/48/000000/express.png" width="40"/> Express		<img src="https://getstream.io/favicon.ico" width="40"/> Stream
<img src="https://vitejs.dev/logo.svg" width="40"/> Vite			<img src="https://www.inngest.com/favicon.ico" width="40"/> Inngest
<img src="https://tailwindcss.com/favicons/favicon-32x32.png" width="40"/> Tailwind CSS			<img src="https://emkc.org/favicon.ico" width="40"/> Piston API
</div>

🚀 Getting Started
Prerequisites
Node.js v18+ & npm

MongoDB (local or Atlas)

Git

🔧 Installation
Clone the repository:



bash
npm install --prefix backend
npm install --prefix frontend
Or use the root script:

bash
npm run build
🔑 Environment Variables
Create .env files in both backend/ and frontend/ folders.

Backend (backend/.env)
env
PORT=3000
NODE_ENV=development

DB_URL=mongodb://localhost:27017/talent-iq

INNGEST_EVENT_KEY=your_inngest_event_key
INNGEST_SIGNING_KEY=your_inngest_signing_key

STREAM_API_KEY=your_stream_api_key
STREAM_API_SECRET=your_stream_api_secret

CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key

CLIENT_URL=http://localhost:5173
Frontend (frontend/.env)
env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_API_URL=http://localhost:3000/api
VITE_STREAM_API_KEY=your_stream_api_key
Note: Replace placeholder values with your actual keys from Clerk, Stream, MongoDB Atlas (if used), and Inngest (optional).

🏃‍♂️ Run the App (Development)
Terminal 1 – Backend

bash
cd backend
npm run dev
Terminal 2 – Frontend

bash
cd frontend
npm run dev
Or run both together from the root (requires concurrently):

bash
npm run dev
Frontend: http://localhost:5173

Backend API: http://localhost:3000

Health check: http://localhost:3000/health

📸 Screenshots
Coming soon – add your own screenshots of the dashboard, code editor, and video call.

🧪 Running Tests
(No tests implemented yet – feel free to contribute!)

🌍 Deployment
Backend (Sevalla / Render / Railway)
Set environment variables on the hosting platform.

Build command: npm install

Start command: npm start

Frontend (Vercel / Netlify)
Set environment variables (VITE_*).

Build command: npm run build

Publish dist folder.

🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to check the issues page.