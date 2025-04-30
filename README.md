✅ Task Management System
This is a simple task management app made for small teams. You can create tasks, assign them to others, track progress, and stay organized.

🌐 Live Demo - 
👉 Click here to try the live app

-----------

🧰 Tech Used
Frontend: Next.js (React)

Backend: Node.js with Express or NestJS

Database: MongoDB or PostgreSQL

Hosted on: Vercel / Render / Railway

-----------

⚙️ How to Run the Project Locally

1. Clone the project
bash
Copy
Edit
git clone https://github.com/your-username/task-manager.git
cd task-manager

2. Install dependencies

For frontend: -
bash
Copy
Edit
cd frontend
npm install

For backend: - 
bash
Copy
Edit
cd backend
npm install

3. Set environment variables
Create a .env file in both folders.

Backend .env example: - 
ini
Copy
Edit
PORT=5000
DATABASE_URL=your_database_link
JWT_SECRET=your_secret_key

Frontend .env example: - 
bash
Copy
Edit
NEXT_PUBLIC_API_URL=http://localhost:5000/api

4. Start the app

Backend: - 
bash
Copy
Edit
npm run dev

Frontend: - 
bash
Copy
Edit
npm run dev

Go to http://localhost:3000 in your browser.

-----------

💡 What This App Can Do - 

Sign up and log in securely

Create tasks with title, description, due date, priority, and status

Assign tasks to other users

See your assigned tasks, created tasks, and overdue tasks

Search and filter tasks easily

-----------

💭 How I Built It (Approach) - 

Started with user login/signup

Then added task features like create, edit, delete

Made sure tasks can be assigned to others

Designed dashboards to show only your tasks

Added filters to help find tasks quickly

Used JWT and bcrypt for secure login

-----------

📝 Things I Assumed / Trade-Offs -

Only basic notifications are added (no real-time WebSocket)

Used MongoDB for faster development (PostgreSQL can also be used)

Didn't add email verification or password reset for now

No roles like Admin/Manager (optional feature)

-----------

🧠 How I Used AI - 

I used ChatGPT to help fix errors and write reusable code

GitHub Copilot helped with suggestions while typing

AI tools saved time and helped with logic building

-----------

✅ Features Done - 

 Login/Signup

 Create and assign tasks

 Task dashboard

 Search and filter

 Mobile-friendly design

-----------

🚀 Extra Features (If You Want to Add More) - 

 Roles like Admin or Manager

 Real-time updates using Socket.io

 Offline support (PWA)

 Analytics dashboard

-----------

📁 Project Structure - 
as show in file formate

