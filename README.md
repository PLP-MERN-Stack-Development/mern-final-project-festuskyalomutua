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
├── client/                     # React frontend
│   ├── public/                 # Static files (index.html, images, etc.)
│   ├── src/                    # React source code
│   │   ├── components/         # Reusable UI components
│   │   ├── pages/              # Page-level components
│   │   ├── context/            # React context providers for state management
│   │   ├── hooks/              # Custom React hooks
│   │   └── socket/             # Socket.io client setup for real-time features
│   └── package.json             # Client dependencies and scripts
├── server/                     # Node.js backend
│   ├── config/                 # Configuration files (DB connection, environment)
│   ├── controllers/            # Route handlers for API endpoints
│   ├── middleware/             # Express middleware functions
│   ├── models/                 # Mongoose schemas and models
│   ├── routes/                 # API route definitions
│   ├── utils/                  # Utility/helper functions
│   └── server.js               # Entry point for the server
├── README.md                   # Project documentation
└── .env                        # Environment variables (server configs, secrets)



