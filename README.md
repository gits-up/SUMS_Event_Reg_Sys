# SUMS_Event_Reg_Sys
An event registration system.

## Tech Stack & Features
- Frontend: React (Vite), TailwindCSS, Axios, React Router
- Backend: Node.js, Express.js
- Database: MongoDB (Mongoose for ORM)
- Authentication: JWT + bcrypt for password hashing
- QR Code Generation: If needed for attendance tracking (using qrcode npm package)
- Storage: Cloudinary (for storing participant profile pictures if required)

## Core Features
- User Authentication (Login/Signup with JWT)
- Event Creation & Management (Admin Panel)
- Participant Registration (Form with validation)
- QR Code for Registration Confirmation (Optional)
- Responsive UI (Mobile-friendly)
- Dashboard for Participants & Admin

## Project Sturcture
- event-registration-system/
- │── backend/                # Node.js + Express Backend
- │   ├── models/             # Mongoose models
- │   ├── routes/             # Express routes
- │   ├── controllers/        # Business logic
- │   ├── middleware/         # Auth middleware (JWT)
- │   ├── config/             # DB & env configuration
- │   ├── server.js           # Main backend entry
- │── frontend/               # React Frontend
- │   ├── src/
- │   │   ├── components/     # Reusable components
- │   │   ├── pages/          # Views (Login, Register, Dashboard)
- │   │   ├── context/        # Global state management
- │   │   ├── App.js          # Entry point
- │   │   ├── index.js        # Main React entry
- │── .env                    # Environment variables
- │── README.md               # Documentation
- │── package.json            # Dependencies
- │── yarn.lock / package-lock.json

