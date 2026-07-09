# School Management System - Development Instructions

## Project Overview
Multi-School MERN Stack Management System supporting Admin, Teacher, and Student roles with JWT authentication, RBAC, real-time notifications, and multi-tenancy (separate admin for each school).

## Tech Stack
- **Frontend**: React 18, Vite, Tailwind CSS, Redux Toolkit, React Router, Axios
- **Backend**: Node.js, Express.js, MongoDB, Mongoose, JWT, bcrypt, Socket.io
- **Database**: MongoDB Atlas
- **Storage**: Cloudinary (for images and documents)
- **Tools**: Multer, PDFKit, ExcelJS, Chart.js/Recharts

## Setup Instructions

### Backend Setup
1. Navigate to backend folder: `cd backend`
2. Install dependencies: `npm install`
3. Create `.env` file with MongoDB URI, JWT secrets, Cloudinary credentials
4. Start server: `npm run dev`

### Frontend Setup
1. Navigate to frontend folder: `cd frontend`
2. Install dependencies: `npm install`
3. Create `.env` file with API URL
4. Start dev server: `npm run dev`

## Key Features
- Multi-school support with separate admins
- Role-Based Access Control (Admin, Teacher, Student)
- JWT Authentication with refresh tokens
- Real-time notifications via Socket.io
- Attendance management with QR/Face recognition ready
- Timetable management with conflict detection
- Marks and examination management
- Homework submission system
- Notice board and complaint management
- Fee management with payment methods
- Analytics and reporting (PDF/Excel export)

## Project Structure
```
school/
├── backend/
│   ├── config/
│   ├── models/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── utils/
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── store/
│   │   ├── services/
│   │   ├── utils/
│   │   └── App.jsx
│   ├── vite.config.js
│   └── package.json
└── README.md
```

## Development Status
- [ ] Backend initialization
- [ ] Frontend initialization
- [ ] Database models and schemas
- [ ] Authentication system
- [ ] API endpoints
- [ ] Frontend components
- [ ] Multi-school architecture
- [ ] Socket.io integration
- [ ] Testing and documentation
