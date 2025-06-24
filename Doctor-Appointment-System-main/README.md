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

**Backend Setup**

1. Install dependencies:
cd backend
npm install

2. Create a .env file in the backend folder and add:
MONGODB_URI=your_mongodb_connection_string
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
JWT_SECRET=your_jwt_secret
RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
ADMIN_EMAIL=admin@example.com
ADMIN_PASSWORD=your_admin_password

3. Start backend server:
npm run dev

**Frontend Setup**

1. Install dependencies:
cd frontend
npm install

2. Create a .env file in the frontend folder:
VITE_BACKEND_URL=http://localhost:4000

3.Start frontend:
npm run dev

**Admin Panel Setup**
1. Install dependencies:
cd admin
npm install

3. Create a .env file in the admin folder (same as backend).

4. Start admin panel:
npm run dev

**🚀 Usage**

1. Register as a patient or doctor or log in as admin.
2. Patients can search doctors, book appointments, and manage their profiles.
3. Doctors can manage schedules and update profiles.
4. Admins can oversee doctors, appointments, and system statistics.
   
**🔍 Core Functionalities**
**Patients:**
Register/Login
Search doctors by specialty
Book/cancel/reschedule appointments
Online payment
Manage profile
**Doctors:**
Manage profile
View appointments
Update appointment status
Track earnings
**Admins:**
Add/manage doctors
Manage all appointments
Toggle doctor availability
View dashboard statistics

**🎨 Customization & Deployment**
Customize UI using Tailwind CSS and React components.
Payment gateways can be switched by updating integration files.
Deploy backend and frontend separately on platforms like Heroku, Vercel, or Netlify.
Secure all environment variables in production.
