✅ Task Management System
This is a simple task management app made for small teams. You can create tasks, assign them to others, track progress, and stay organized.

🌐 Live Demo - 
👉 
![Screenshot (1093)](https://github.com/user-attachments/assets/a814305e-162d-4a39-be98-f65325334912)

![Screenshot (1094)](https://github.com/user-attachments/assets/363ab663-d059-4745-b5a7-858009bbc463)

![Screenshot (1095)](https://github.com/user-attachments/assets/0bb81096-a21a-4cfd-8da3-5ce3c2cd9ae8)

![Screenshot (1096)](https://github.com/user-attachments/assets/1711483b-1431-4c6e-aafc-f4b5a0d6828c)

![Screenshot (1097)](https://github.com/user-attachments/assets/ffdf7645-fbb6-4bed-8e31-dfe6a8847d93)

![Screenshot (1098)](https://github.com/user-attachments/assets/394c851f-59ac-4324-8eb2-da09ea548d4f)

![Screenshot (1099)](https://github.com/user-attachments/assets/e9b63bfe-3d4c-47b3-80ec-462a3248e0ff)

![Screenshot (1100)](https://github.com/user-attachments/assets/1b7867f0-7801-415a-8e99-eeb99b59e175)

![Screenshot (1101)](https://github.com/user-attachments/assets/f777e35a-29f8-4084-b4f1-82f1f881e647)

![Screenshot (1102)](https://github.com/user-attachments/assets/ba429808-297c-425d-94b2-82e2bf6c7729)


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

