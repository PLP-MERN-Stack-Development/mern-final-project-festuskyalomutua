# LearnLink Kenya CBE

**LearnLink Kenya CBE** is a web platform designed to facilitate Competency-Based Education (CBE) in Kenya. It serves as a comprehensive system connecting students, teachers, and administrators, enabling effective content management, real-time communication, assessments, and robust progress tracking tailored to the specific educational framework.

## Overview

This platform aims to modernize the educational experience by providing a centralized digital hub for all stakeholders. It supports the dynamic requirements of a competency-based model, focusing on skill acquisition and measurable outcomes rather than traditional metrics.

---

## <details> <summary>🚀 Features</summary>

*   **Authentication & Roles:** Secure sign-in systems for Students, Teachers, and Admins.
*   **Course Management:** Intuitive interfaces to create, update, and manage educational courses.
*   **Assessments:** Tools for quizzes, assignments, and detailed feedback mechanisms.
*   **Real-Time Messaging:** Instant notifications and live chat functionality to enhance collaboration.
*   **Progress Tracking:** Detailed dashboards to monitor student competency achievements and progress.
*   **Responsive UI:** A user interface that works seamlessly on both desktop and mobile devices.

</details>

## <details> <summary>📸 Screenshots</summary>

*(Screenshots of the Login page, Dashboard, and Messaging interface would be included here)*

</details>

## 📂 Project Structure

The project follows a typical full-stack architecture, separating the client-side React application from the Node.js/Express server.

Use code with caution.

learnlink-kenya-cbe/
├── client/ # React frontend
│ ├── src/ # Components, pages, context, hooks, socket connections
│ └── package.json # Client dependencies
├── server/ # Node.js backend
│ ├── config/ # Database & environment configuration
│ ├── controllers/ # Logic for handling requests
│ ├── middleware/ # Express middleware (e.g., authentication)
│ ├── models/ # Mongoose schemas/models
│ ├── routes/ # API routes definitions
│ ├── utils/ # Utility functions
│ └── server.js # Backend entry point
├── README.md # Project documentation (this file)
└── .env.example # Template for environment variables

Getting Started
Prerequisites

Node.js (v18+)

npm or yarn

MongoDB (local or Atlas)

Git

Installation
# Clone the repository
git clone https://github.com/festuskyalomutua/learnlink-kenya-cbe.git
cd learnlink-kenya-cbe

# Install server dependencies
cd server
npm install

# Install client dependencies
cd ../client
npm install

Environment Setup

Create a .env file in the server folder:

PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

Running the Application
# Start backend server
cd server
npm start

# Start frontend client
cd ../client
npm start


Server: http://localhost:5000

Client: http://localhost:3000

Deployment

Build React client for production:

cd client
npm run build


Serve the build folder with Express or deploy separately on Vercel/Render.

Use environment variables for database connections and secrets.

Authors

Festus Kyalo Mutua

GitHub: festuskyalomutua

License

Educational project for Competency-Based Education (CBE) support in Kenya.



