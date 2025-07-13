👨‍💼 Employee Management System

A full-stack-like employee and admin dashboard system built completely on the frontend using React, styled with Tailwind CSS, powered by Vite, and using Context API for state management. Data is stored using localStorage so the app works without a backend.

🖼️ Demo
(https://employee-management-system-iota-rose.vercel.app/)


✨ Key Features
🧑‍💼 Role-Based Dashboards
Employee Dashboard: View assigned tasks and profile data

Admin Dashboard: Create, assign, and manage all tasks and users

🔐 Authentication
Context-based login for both admin and employee roles

Session persistence using localStorage

🧠 Context API State Management
AuthContext: Handles authentication and current user

TaskContext: Manages task creation, updates, and filtering

📋 Task Management System
Admins can assign tasks to employees

Employees see only their own tasks

Data is retained via local storage

⚡ Performance-First Build
Vite for blazing-fast development and build

Tailwind CSS for responsive and utility-first styling

🛠️ Tech Stack
Category	Tools/Technologies
Frontend	React, JSX
Build Tool	Vite
Styling	Tailwind CSS
Routing	React Router DOM
State Mgmt	React Context API (useContext)
Storage	Browser localStorage
Development	npm, VS Code

📂 Project Structure
pgsql
Copy
Edit
employee-management-system/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── AdminDashboard.jsx
│   │   ├── EmployeeDashboard.jsx
│   ├── context/
│   │   ├── AuthContext.jsx
│   │   ├── TaskContext.jsx
│   ├── pages/
│   │   ├── Login.jsx
│   │   ├── AdminPage.jsx
│   │   ├── EmployeePage.jsx
│   ├── utils/
│   │   └── localStorageUtils.js
│   ├── App.js
│   └── main.jsx
├── index.html
├── package.json
├── package-lock.json
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
🧪 Getting Started
🔧 Prerequisites
Make sure you have:

Node.js ≥ 16

npm or yarn

📥 Installation
Clone the repository and install dependencies:

bash
Copy
Edit
git clone https://github.com/ITSEEFAT/employee-management-system.git
cd employee-management-system
npm install
▶️ Run the App
bash
Copy
Edit
npm run dev
Open http://localhost:5173 to view the app in your browser.

🧠 Learnings
This project helped reinforce:

Proper separation of roles and responsibilities in UI

Advanced usage of React Context API

Integration of Tailwind CSS for quick UI development

How to manage app state and session without a backend

Creating a modular and scalable folder structure

📌 Future Improvements
 Connect to a real backend (Node.js / Firebase / Supabase)

 Add password-based authentication

 Search & filter tasks

 Task completion status

 Mobile responsive enhancements

🙌 Acknowledgements
Built as a personal learning project

UI data partially generated with help from ChatGPT

Special thanks to [Akshay Saini] for guidance and support

📃 License
This project is licensed under the MIT License.

💬 Connect with Me
GitHub: @ITSEEFAT

LinkedIn: (https://www.linkedin.com/in/seefat12/)

Portfolio: (https://employee-management-system-iota-rose.vercel.app/)