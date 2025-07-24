# ToolAmaze

ToolAmaze is a modern full-stack web application that unifies a range of productivity tools—like text converters, code formatters, and utility generators—into a single, easy-to-use platform. Built for the **Web Engineering** course at **Capital University of Science and Technology (CUST)**, this project demonstrates practical implementation of a scalable, role-based utility platform.

---

## 📖 About

In today's digital era, individuals and small teams waste time switching between scattered “microtool” websites. ToolAmaze solves this by centralizing multiple tools behind a single login with personalized access. Users see only what they need, while admins can manage tools, assign access, and handle platform content securely.

---

## ✨ Features

* 🔒 **User Authentication** — Secure login and role-based access (users/admins).
* 🛠️ **Tool Management** — Admins can add, edit, delete, and assign tools to users.
* 🗂️ **Dynamic Dashboard** — Users see only the tools they own.
* 📈 **Clean UI** — Fast, responsive SPA using React, Vite, Tailwind, and Bootstrap.
* 🔗 **External Tools Integration** — Launch tools in new tabs.
* ⚙️ **RESTful API** — Built with Node.js, Express, and MySQL.
* 🔐 **Security** — Parameterized SQL, middleware validation, and role-based routes.

---

## 🛠️ Technology Stack

**Frontend**

* React 18
* Vite 5
* TailwindCSS 4
* Bootstrap utility classes
* FontAwesome

**Backend**

* Node.js 20
* Express 4
* MySQL 8 (mysql2 driver)

**Database**

* Tables: `users`, `admin`, `tools`, `assignment` (many-to-many mapping)

---

## 📂 Project Structure

```
ToolAmaze/
 ├── client/            # React frontend (Vite)
 │   ├── src/pages      # Home, Pricing, Contact, Login, Register, Dashboard, Admin
 │   ├── src/components # Navbar, Footer, Cards, Buttons
 │   ├── App.jsx        # Routing & Layout
 ├── server/            # Node.js backend
 │   ├── routes/        # Auth, Tool CRUD, Assignments
 │   ├── db/            # MySQL connection
 │   ├── middleware/    # Validation, error handling
 ├── README.md
```

---

## 🚀 How to Run

1️⃣ **Clone the repository**

```bash
git clone https://github.com/yourusername/ToolAmaze.git
cd ToolAmaze
```

2️⃣ **Install dependencies**

```bash
# Frontend
cd client
npm install

# Backend
cd ../server
npm install
```

3️⃣ **Setup database**

* Create a MySQL database.
* Run the provided schema to create `users`, `admin`, `tools`, `assignment` tables.

4️⃣ **Run backend**

```bash
cd server
node index.js
```

5️⃣ **Run frontend**

```bash
cd client
npm run dev
```

---

## 🗺️ Roadmap

✔️ **Current**

* Local authentication & role management
* Admin dashboard for CRUD & tool assignment

🔜 **Planned**

* Cloud database hosting (AWS RDS)
* JWT-based secure sessions
* Stripe payment integration
* Analytics & usage tracking
* PWA support for offline access

---

## 👨‍💻 Contributors

* **Syed Mukhtar ul Hassan** — BSE223208
* **Muhammad Abbas** — BSE223183
* **Muhammad Hammad Ali** — BSE223005

**Instructor:** Dr. Muhammad Furqan
**Course:** Web Engineering
**Semester:** Spring 2025
**Institution:** Capital University of Science and Technology (CUST)

---

## 📄 License

This project is for educational purposes only. Feel free to fork and build on it!


