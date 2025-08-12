MEETMEUP


A backend implementation for a Zoom-like video conferencing platform built with Node.js, Express, Socket.IO, and MongoDB.
This server handles real-time communication, user authentication, and room management for the Meetmeup video chat application.

🚀 Features
Real-time video & audio communication (via WebRTC & Socket.IO)

User authentication (secure password storage with bcrypt)

Room creation & joining functionality

Persistent data storage with MongoDB & Mongoose

Real-time messaging in video rooms

Error handling with http-status

Scalable & production-ready with PM2 support

🛠 Tech Stack
Backend Framework: Express
Database: MongoDB with Mongoose
Real-time Communication: Socket.IO
Authentication: bcrypt for password hashing
Utilities: crypto, http-status for cleaner APIs
Dev Tools: Nodemon for development, PM2 for production

📂 Project Structure
bash
Copy
Edit
Backend/
│── src/
│   ├── app.js          # Main server file
│   ├── routes/         # API routes
│   ├── controllers/    # Request handlers
│   ├── models/         # MongoDB models
│   ├── utils/          # Utility functions
│── package.json
⚙️ Installation & Setup
1️⃣ Clone the repository
bash
Copy
Edit
git clone https://github.com/your-username/meetmeup.git
cd meetmeup/Backend
2️⃣ Install dependencies
bash
Copy
Edit
npm install
3️⃣ Set up environment variables
Create a .env file in the Backend/ folder with the following:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
4️⃣ Run the backend server
Development mode (with auto-reload):
bash
Copy
Edit
npm run dev
Production mode:
bash
Copy
Edit
npm start
With PM2:
bash
Copy
Edit
npm run prod
