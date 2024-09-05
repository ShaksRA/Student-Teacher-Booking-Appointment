# Student-Teacher-Booking-Appointment

Student-Teacher Booking Appointment System
This is a MERN stack project designed to facilitate the booking of appointments between students and teachers. The system includes functionalities for admins to manage teachers, for teachers to manage their appointments, and for students to book appointments with teachers.

Table of Contents
Features
System Modules
Admin
Teacher
Student
Tech-Stack-Used
Installation
Usage
Screenshots
Login Acess
Contributing
Features
Admin management for adding, updating, and deleting teachers and approving student registrations.
Teacher functionalities for managing their appointment schedules, approving/cancelling appointments, sending email alerts to students, viewing messages, and viewing all appointments.
Student functionalities for registering, booking appointments with teachers, sending email alerts to teachers, and sending messages.
System Modules
Admin
Add Teacher (Name, Department, Subject, etc.)
Update/Delete Teacher
Approve Registration Student
Teacher
Login
Schedule Appointment
Approve/Cancel Appointment
Send Email Alerts to Students
View Messages
View All Appointments
Student
Register
Login
Book Appointment
Send Email Alert to Teacher
Send Message
Tech-Stack-Used
Frontend

vite (bundler-react)
tailwindcss (styling)
react-icons (icons)
react-router-dom (routing)
react-toastify (notify)
axios (API)
Backend

express (API)
jwt-token (token)
nodemail (MAIL)
bcrypt (encryption)
Installation
To run this project locally, follow these steps:

Clone the repository:

git clone https://github.com/rudrax14/MERN_STACK-StudentTeacher-Booking-Appointment
Install backend dependencies:

cd backend
npm install
Install frontend dependencies:

cd frontend
npm install
Set up environment variables for the backend:

Create a .env file in the backend directory with the following content:

DB_URL=''
JWT_KEY = ''
PORT = 5000

# mail integration 

MAIL_HOST = smtp.gmail.com
MAIL_USER = 'your_mail'
MAIL_PASS = 
Run the backend server:

cd backend
npm run dev
Run the frontend server:

cd frontend
npm run dev
Set up environment variables for frontend:

Create a .env.local file in the frontend directory with the following content:

VITE_BACKEND_URL='http://localhost:5000'
The application should now be running on http://localhost:5173/.

Usage
Admin:

Log in to the admin dashboard.
Add, update, or delete teachers.
Approve student registrations.
Teacher:

Log in to the teacher portal.
Schedule, approve, or cancel appointments.
Send email alerts to students.
View messages and all appointments.
Student:

Register and log in to the student portal.
Book appointments with teachers.
Send email alerts and messages to teachers.
Screenshots
Landing Page

landingpage Dark

Student Dashboard

student dashboard dark

Teacher Dashboard

teacher d Dark

Admin Dashboard

admin 

Login
Student

email: student@gmail.com
Password: pass123
Teacher

email: teacher@gmail.com
Password: pass123
Admin

email: admin@gmail.com
Password: admin
Note: Don't Spam

Contributing
Contributions are welcome! Please follow these steps:

Fork the repository.
Create your feature branch: git checkout -b feature/YourFeature
Commit your changes: git commit -m 'Add some feature'
Push to the branch: git push origin feature/YourFeature
Open a pull request.
Thank You
Keep Coding
