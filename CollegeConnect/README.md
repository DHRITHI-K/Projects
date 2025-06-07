College Connect — Student-Faculty Portal
A role-based web portal that allows students and faculty to interact, share academic content, and track performance securely.

Features -
JWT-based login/signup for students and faculty
Role-specific access to upload/view notes and assignments
MongoDB-based user and content management
Secure password hashing with bcrypt

Tech Stack -
Backend: Node.js, Express.js
Database: MongoDB (Mongoose)
Auth: JWT, bcryptjs
Frontend: HTML, CSS, JavaScript (or React - optional)

How to Run:
npm install
node app.js

Create a .env file:
MONGO_URI=your_mongo_uri
JWT_SECRET=your_secret_key
