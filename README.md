LearnLink Kenya CBE
Overview

LearnLink Kenya CBE is a web-based platform designed to support competency-based education (CBE) in Kenya. The application connects students, teachers, and administrators through a centralized system for managing learning content, assessments, and real-time communication.

Features

1.User Authentication & Roles: Secure login for students, teachers, and admins

2.Course Management: Teachers can create, update, and manage course content

3.Assessments: Students can submit assignments, take quizzes, and receive feedback

4.Real-Time Communication: Notifications and messaging between users

5.Progress Tracking: Monitor student performance and competency achievement

6.Responsive UI: Accessible on both desktop and mobile devices

learnlink-kenya-cbe/
│
├── client/                     # React frontend
│   │
│   ├── public/                 # Static files (index.html, images, etc.)
│   ├── src/                    # React source code
│   │   ├── components/         # Reusable UI components
│   │   ├── pages/              # Page-level components
│   │   ├── context/            # React context providers
│   │   ├── hooks/              # Custom React hooks
│   │   └── socket/             # Socket.io client setup
│   └── package.json             # Client dependencies and scripts
│
├── server/                     # Node.js backend
│   │
│   ├── config/                 # Configuration files (DB connection, environment)
│   ├── controllers/            # API route handlers
│   ├── middleware/             # Express middleware functions
│   ├── models/                 # Mongoose schemas and models
│   ├── routes/                 # API route definitions
│   ├── utils/                  # Utility/helper functions
│   └── server.js               # Server entry point
│
├── README.md                   # Project documentation


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


