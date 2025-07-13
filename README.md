
<h1 align="center">👨‍💼 Employee Management System</h1>

<p align="center">
  A modern, role-based task management dashboard built with <strong>React</strong>, <strong>Vite</strong>, and <strong>Tailwind CSS</strong>.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/React-18.x-blue?logo=react" />
  <img src="https://img.shields.io/badge/Vite-5.x-purple?logo=vite" />
  <img src="https://img.shields.io/badge/TailwindCSS-3.x-38bdf8?logo=tailwindcss" />
  <img src="https://img.shields.io/badge/License-MIT-green" />
</p>

---

## 🔗 Live Demo

🌐 **Deployed App:** [Click here to explore the app live 🚀](https://employee-management-system-iota-rose.vercel.app/)

---

## 🔐 Demo Login Credentials

| Role     | Email           | Password |
|----------|------------------|----------|
| 👨‍💼 Admin    | `admin@me.com`   | `123`     |
| 👷 Employee | `e@e.com`        | `123`     |

---

## 🚀 Features

- 🔐 Role-Based Login System using React Context
- 👨‍💼 Admin Dashboard: View and assign tasks to employees
- 👷 Employee Dashboard: View assigned tasks and personal profile
- 📋 Task management via Context API
- 💾 Data Persistence with localStorage
- ⚡ Powered by Vite for blazing-fast builds and HMR
- 🎨 Fully Responsive UI with Tailwind CSS
- 🧩 Modular and Reusable Components

---

## 🛠️ Tech Stack

| Category        | Tools Used                         |
|-----------------|------------------------------------|
| 🚀 Frontend      | React, Vite, JSX                   |
| 🧠 State Mgmt     | React Context API, useState, useEffect |
| 🎨 Styling       | Tailwind CSS                      |
| 🌐 Routing       | React Router DOM                  |
| 💾 Storage       | localStorage                      |

---

## 📁 Folder Structure

```
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
├── postcss.config.js
├── tailwind.config.js
├── vite.config.js
```

---

## 📦 Getting Started

To run this project locally:

1️⃣ Clone the repo:

```bash
git clone https://github.com/ITSEEFAT/employee-management-system.git
cd employee-management-system
```

2️⃣ Install dependencies:

```bash
npm install
```

3️⃣ Start the dev server:

```bash
npm run dev
```

Visit `http://localhost:5173` to open the app in your browser.

---

## 🧠 How It Works

- AuthContext manages login/logout and role-based state
- TaskContext handles task data and distribution
- Admin users are redirected to the Admin Dashboard
- Employee users view only their assigned tasks
- All session and task data is stored using browser `localStorage`

---

## 📚 Learning Highlights

- ✅ React Context API in real-world use
- ✅ Role-based authentication flow
- ✅ Client-side routing with React Router
- ✅ Styling with Tailwind’s utility-first approach
- ✅ Fast dev & production builds using Vite

---

## 🙌 Special Thanks

A huge shoutout and heartfelt thanks to **[Akshay Saini](https://www.linkedin.com/in/akshaymarch7/)** for his amazing **Namaste React** course, which was my primary source for learning and mastering React.js fundamentals. 🙏

---

## 👨‍💻 About Me

**Syed Seefatul Haque**  
Aspiring Frontend Developer passionate about React, UI design, and building meaningful web experiences.

📇 **LinkedIn:** [www.linkedin.com/in/seefat12](https://www.linkedin.com/in/seefat12)  
📫 **Email:** [seefat12@gmail.com](mailto:seefatprofessional@gmail.com)

Feel free to connect! I’m always open to collaboration, learning, and building cool things together.

---

## 📃 License

This project is open-sourced under the **MIT License** — use it freely for personal or academic purposes.
See the [LICENSE](./LICENSE) file for more details.

---

## 🔮 Future Enhancements

- 🔒 Add password encryption / OAuth integration
- 🌐 Firebase or Supabase backend support
- 📊 Admin analytics dashboard
- 🗂️ Task filters and search functionality
- 📨 Email notifications/reminders
