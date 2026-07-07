<!-- ========================================================= -->

<!--                     ATTENDIFY README                       -->

<!-- ========================================================= -->

<h1 align="center">
  📚 Attendify
</h1>

<h3 align="center">
A Modern Full-Stack Attendance Management System for Students
</h3>

<p align="center">
Track • Analyze • Improve Attendance
</p>

<p align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=28&pause=1000&color=4F46E5&center=true&vCenter=true&width=700&lines=Smart+Attendance+Management;Built+with+the+MERN+Stack;Interactive+Dashboard;Attendance+Analytics;Simple+Fast+Reliable" />

</p>

---

<p align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge\&logo=react\&logoColor=61DAFB)
![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge\&logo=nodedotjs\&logoColor=white)
![Express](https://img.shields.io/badge/Express-black?style=for-the-badge\&logo=express)
![MongoDB](https://img.shields.io/badge/MongoDB-13AA52?style=for-the-badge\&logo=mongodb\&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-black?style=for-the-badge\&logo=jsonwebtokens)

</p>



---

# ✨ Overview

**Attendify** is a modern MERN Stack web application built to simplify attendance management.

Instead of maintaining attendance manually, users can record attendance with one click, monitor subject-wise percentages, visualize attendance trends, and access detailed attendance history—all from a clean and responsive dashboard.

Whether it's **Classes** or **Labs**, Attendify keeps everything organized in one place.

---

# 🚀 Live Demo

### 🌐 Website

https://frontend-bay-iota-86.vercel.app/



---

# ✨ Features

| Feature                 | Description                           |
| ----------------------- | ------------------------------------- |
| 🔐 Authentication       | Secure Login & Registration using JWT |
| 📊 Dashboard            | One-click attendance marking          |
| 📚 Subject Management   | Add/Delete Subjects                   |
| 🧪 Class & Lab Support  | Separate attendance tracking          |
| 📈 Attendance Analytics | Interactive charts                    |
| 📜 Attendance History   | Date-wise Present/Absent records      |
| 📱 Responsive UI        | Works on Desktop, Tablet & Mobile     |
| ⚡ Fast Performance      | Optimized MERN architecture           |

---

# 🎯 Key Highlights

✅ JWT Authentication

✅ Responsive Design

✅ Subject-wise Attendance

✅ Attendance Percentage Calculator

✅ Interactive Graphs

✅ Attendance History

✅ CRUD Operations

✅ Clean UI

---

# 🛠 Tech Stack

<table>

<tr>

<td align="center">

<img width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">

<br>

React

</td>

<td align="center">

<img width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">

<br>

Node.js

</td>

<td align="center">

<img width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original.svg">

<br>

Express

</td>

<td align="center">

<img width="70" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original.svg">

<br>

MongoDB

</td>

</tr>

</table>

---

# 🏗 System Architecture

```text
                    +----------------------+
                    |      React.js        |
                    |      Frontend        |
                    +----------+-----------+
                               |
                               |
                        REST API Calls
                               |
                               ▼
                    +----------------------+
                    |      Express.js      |
                    |      Node.js API     |
                    +----------+-----------+
                               |
                JWT Authentication Middleware
                               |
                               ▼
                    +----------------------+
                    |      MongoDB         |
                    | Attendance Database  |
                    +----------------------+
```

---

# 📂 Folder Structure

```text
Attendify/
│
├── client/
│   ├── public/
│   │
│   ├── src/
│   │   ├── api/
│   │   │   └── axios.js
│   │   │
│   │   ├── assets/
│   │   │   ├── images/
│   │   │   ├── icons/
│   │   │   └── logo.png
│   │   │
│   │   ├── components/
│   │   │   ├── Navbar.jsx
│   │   │   ├── Navbar.css
│   │   │   ├── MarkAttendence.jsx
│   │   │   ├── MarkAttendance.css
│   │   │   ├── Home.jsx
│   │   │   ├── Home.css
│   │   │   ├── AttendanceAnalytics.jsx
│   │   │   ├── AttendanceAnalytics.css
│   │   │   ├── AttendanceHistory.jsx
│   │   │   ├── AttendanceHistory.css
│   │   │   ├── Login.jsx
│   │   │   ├── Login.css
│   │   │   ├── Register.jsx
│   │   │   ├── Register.css
│   │   │   ├── Dashboard.jsx
│   │   │   ├── Dashboard.css
│   │   │   ├── SubjectManager.jsx
│   │   │   ├── SubjectManager.css
│   │   │   ├── SubjectSelect.jsx
│   │   │   ├── SubjectSelect.css
│   │   │   └── ParticleBackground.jsx
│   │   │
│   │   │
│   │   │
│   │   ├── App.jsx
│   │   ├── main.jsx
│   │   ├── App.css
│   │   └── index.css
│   │
│   └── package.json
│
├── server/
│   │
│   ├── node_module/
│   │
│   ├── middleware/
│   │
│   ├── models/
│   │
│   ├── routes/
│   │
│   │
│   ├── server.js
│   ├── .env
│   └── package.json
│
│
├── .gitignore
├── README.md
└── package.json (optional)
```

---

# ⚙ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Attendify.git
```

## Install Dependencies

```bash
cd Attendify

cd client
npm install

cd ../server
npm install
```

---

# 🔑 Environment Variables

Create a `.env` file inside the server folder.

```env
PORT=5000

MONGO_URI=YOUR_MONGODB_URI

JWT_SECRET=YOUR_SECRET_KEY
```

---

# ▶ Run the Project

Backend

```bash
npm run dev
```

Frontend

```bash
cd client
npm run dev
```

---

# 📊 Future Improvements

* 📅 Calendar View
* 📤 Export Attendance Reports
* 📧 Email Notifications
* 🌙 Dark Mode
* 📱 Mobile App
* 👨‍🏫 Teacher Dashboard
* 📈 Advanced Analytics
* 🔔 Attendance Reminders



---

# 🤝 Contributing

Contributions are welcome.

```bash
Fork → Create Branch → Commit → Push → Pull Request
```

---

# 🌟 Support

If you found this project helpful,

⭐ Star the repository

🍴 Fork it

🛠 Contribute

📢 Share it

---

# 👨‍💻 Developer

**Aradhya Patel**

Email-:[aradhyapatel139@gmail.com]

---

<p align="center">

Made with ❤️ using the MERN Stack

</p>

<p align="center">

⭐ If you like this project, don't forget to star the repository!

</p>
