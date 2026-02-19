Online Complaint Registration & Management System

ResolveNow is a full-stack web application designed to streamline the process of registering, tracking, assigning, and resolving customer complaints efficiently.
It provides separate dashboards for Customers, Agents, and Admins, ensuring structured complaint handling with real-time updates and secure communication.

🚀 Features
User Registration & Login (JWT Authentication)
Submit Complaints with Details & Attachments
Real-time Complaint Status Tracking
Agent Assignment & Complaint Routing
Built-in Chat Between User and Agent
Admin Dashboard for Monitoring & Management
Secure Data Storage using MongoDB
Role-Based Access Control (User / Agent / Admin)

🛠️ Technologies Used
Frontend
React.js
Bootstrap
Material UI
Axios
Backend
Node.js
Express.js
MongoDB
Mongoose
JWT Authentication
Socket.io

⚙️ How to Run the Project (Terminal Commands)
1️⃣ Clone the Repository
git clone <your-repository-link>
cd ResolveNow

2️⃣ Run Backend
Open terminal and run:
cd backend
npm install
node server.js

Backend will run on:
http://localhost:5000

3️⃣ Run Frontend
Open another terminal and run:
cd frontend
npm install
npm start

Frontend will run on:
http://localhost:3000

🔐 Environment Variables
Create a .env file inside the backend folder and add:
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

📊 Output
Users can register and submit complaints.
Admin assigns complaints to agents.
Agents update complaint status.
Users receive real-time updates and can chat with agents.
Complaints are resolved and feedback is collected.
