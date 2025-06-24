**Doctor Appointment Booking System**
A full-stack web application built using the MERN Stack (MongoDB, Express.js, React.js, Node.js) for seamless doctor appointment booking and management.
The system supports multi-role authentication and separate dashboards for patients, doctors, and admins.

**🔑 Key Features**
**Multi-Role Authentication:**
Separate login and dashboards for patients, doctors, and admins.
**Doctor Management:**
Admins can add doctors with profile images, specialties, experience, and fees.
Doctors can manage their profiles and availability.
**Patient Features:**
Patients can search doctors by specialty, view top doctors, book appointments, and manage their profiles.
**Appointment Booking:**
Real-time slot availability, online booking, rescheduling, and cancellation.
**Payment Integration:**
Secure online payments via Razorpay.
**Responsive UI:**
Built with React.js and Tailwind CSS for a modern, mobile-friendly interface.
**Profile Management:**
Both patients and doctors can update profiles and upload images using Cloudinary.
**Admin Panel:**
Admins can manage doctors, appointments, and track dashboard statistics.
**Notifications:**
Real-time user feedback via toast notifications.
**State Management:**
Shared state using React Context API.

**🛠️ Technologies Used**
Frontend: React.js, Tailwind CSS, React Router DOM, React Toastify, Axios
Backend: Node.js, Express.js, Mongoose, bcrypt, JWT, multer, Cloudinary, cors, dotenv, validator, nodemon
Database: MongoDB (MongoDB Atlas)
Payment Gateway: Razorpay
State Management: React Context API, useState, useEffect

**⚙️ Installation & Setup**

1. Clone the repository: git clone https://github.com/md0011/Doctor-Appointment-System
2. Install dependencies: npm install or yarn install
3. Create a .env file in the root directory and set environment variables for database connection, authentication, and other configurations.
4. Start the development server: npm start or yarn start

🚀 Usage
1.Register as a patient or doctor or log in as admin.
2.Patients can search doctors, book appointments, and manage their profiles.
3.Doctors can manage schedules and update profiles.
4.Admins can oversee doctors, appointments, and system statistics.
