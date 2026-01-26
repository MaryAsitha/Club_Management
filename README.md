# 🎓 **Club Management System**



A full-stack Club Management System designed to manage college club activities such as members, events, announcements, attendance, bus timings, monitoring, and dashboard analytics.

The project is built with a modular backend architecture and is planned to integrate Geo-attendance and Wi-Fi–based attendance as future enhancements.



## 🚀 Features

##### Member Management



Add, view, and delete club members



Role-based members (President, Vice President, Secretary, Member)



##### Event Management



Create and manage club events



Track event schedules, venues, and descriptions

##### 

##### Announcements



Post important club announcements



View and manage announcements centrally



##### Bus Timings



Manage college/club-day bus schedules



Easy access for students



##### Attendance Management



Mark attendance for events



Store attendance records per member



Designed for future Geo \& Wi-Fi attendance integration



##### Dashboard



Total members, events, announcements



Role distribution (for charts)



Events per month statistics



##### Monitoring



Monitor absentee records



Identify frequently absent members



### 🛠 Tech Stack

Backend



Node.js



Express.js



MongoDB Atlas



Mongoose



dotenv



Frontend (In Progress)



React (Vite)



Bootstrap / CSS



Tools



Postman – API testing



Git \& GitHub – Version control



### 📂 Project Structure

club-management/

│

├── backend/

│   ├── config/

│   │   └── db.js

│   │

│   ├── controllers/

│   │   ├── announcementController.js

│   │   ├── attendanceController.js

│   │   ├── busController.js

│   │   ├── dashboardController.js

│   │   ├── eventController.js

│   │   ├── memberController.js

│   │   └── monitoringController.js

│   │

│   ├── models/

│   │   ├── Announcement.js

│   │   ├── Attendance.js

│   │   ├── Bus.js

│   │   ├── Event.js

│   │   └── Member.js

│   │

│   ├── routes/

│   │   ├── announcementRoutes.js

│   │   ├── attendanceRoutes.js

│   │   ├── busRoutes.js

│   │   ├── dashboardRoutes.js

│   │   ├── eventRoutes.js

│   │   ├── memberRoutes.js

│   │   └── monitoringRoutes.js

│   │

│   ├── .env

│   └── server.js

│

└── frontend/ (React – under development)



### ⚙️ Installation \& Setup

1️⃣ Clone the Repository

git clone https://github.com/your-username/club-management.git

cd club-management/backend



2️⃣ Install Dependencies

npm install



3️⃣ Environment Variables



Create a .env file inside backend/:



MONGO\_URI=your\_mongodb\_atlas\_connection\_string

PORT=5000



4️⃣ Run the Server

npm start





Server will run at:



http://localhost:5000



🧪 API Testing (Postman)



All backend APIs are tested using Postman.



###### Sample Endpoints:



GET /api/members



POST /api/members



GET /api/events



GET /api/dashboard



GET /api/monitoring



👉 Postman testing ensures backend stability before frontend integration.



### Future Enhancements



📍 Geo-Attendance (GPS based)



📶 Wi-Fi based Attendance (Zone / Venue based)



📱 Mobile-friendly UI



🔐 Authentication \& Role-based Access



📊 Advanced analytics \& reports



🎯 Project Purpose



This project is developed as:



Academic Year Project. Its Real-world scalable club management solution.



***Author***



***Priya Dharshini B***

***Tech Student | Full-Stack Developer***

***Focused on MERN, System Design \& Research-based solutions***

