TEAM TASK MANAGER (FULL STACK)

1. PROJECT OVERVIEW
Team Task Manager is a full-stack web application that allows users to create projects, assign tasks, and track progress within a team. The system uses role-based access control where Admins can manage projects and tasks, while Members can view and update their assigned work.
This project is built as part of an assignment to demonstrate full-stack development skills including frontend, backend, database integration, and authentication.

2. FEATURES

* User Authentication (Signup and Login)
* Role-Based Access (Admin / Member)
* Project Creation and Management
* Task Creation and Assignment
* Task Status Tracking (Pending, In Progress, Completed)
* Dashboard for tracking tasks and overdue work
* Secure REST APIs with validation



3. TECH STACK
Frontend:

* React.js

Backend:

* Node.js
* Express.js

Database:

* MongoDB (via MongoDB Atlas)

Authentication:

* JWT (JSON Web Token)



4. PROJECT STRUCTURE
/frontend   -> Contains React UI and client-side code
/backend    -> Contains server, APIs, database models


5. INSTALLATION & SETUP
Step 1: Clone the repository
git clone https://github.com/AnanyaGupta122/Team-Task-Manager.git

Step 2: Install dependencies

For Backend:
cd backend
npm install

For Frontend:
cd frontend
npm install

Step 3: Setup environment variables

Create a .env file inside backend folder and add:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

Step 4: Run the application

Start Backend:
cd backend
npm start

Start Frontend:
cd frontend
npm run dev



6. API ENDPOINTS (BASIC)
Authentication:

* POST /api/auth/register
* POST /api/auth/login

Projects:

* POST /api/projects
* GET /api/projects

Tasks:

* POST /api/tasks
* GET /api/tasks
* PUT /api/tasks/:id



7. ROLE BASED ACCESS
Admin:

* Create and manage projects
* Assign tasks to users
* View all tasks

Member:

* View assigned tasks
* Update task status


8. FUTURE IMPROVEMENTS
* Email notifications
* File attachments in tasks
* Real-time updates using Socket.io
* Improved UI/UX


9. CONCLUSION
This project demonstrates how a full-stack application works using modern technologies. It covers authentication, API development, database handling, and frontend integration.
