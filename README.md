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
├── client/                 # React frontend
│   ├── public/
│   ├── src/
│   │   ├── components/     # UI components
│   │   ├── pages/          # Page-level components
│   │   ├── context/        # React context providers
│   │   ├── hooks/          # Custom React hooks
│   │   └── socket/         # Socket.io setup
│   └── package.json
├── server/                 # Node.js backend
│   ├── config/             # DB and environment configs
│   ├── controllers/        # API route handlers
│   ├── middleware/         # Express middleware
│   ├── models/             # MongoDB models
│   ├── routes/             # API routes
│   ├── utils/              # Utility functions
│   └── server.js
├── README.md
└── .env                    # Environment variables


