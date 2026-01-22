# VibeCheck--Eliana-Nase-Perez-
Act 3

## 📌 Project Overview

**VibeCheck** is a simple full-stack web application created for **CPE 411L – Act 3**.
The project demonstrates how a **Node.js + Express backend API** can communicate with a **frontend UI** using buttons and HTTP requests.

Users can click different buttons on the frontend to fetch data from the backend such as fortunes, jokes, mood-based responses, and a smash counter.

---

## 🛠 Technologies Used

* **Node.js**
* **Express.js**
* **CORS**
* **HTML / JavaScript (Frontend)**
* **Git & GitHub (Branching and Pull Requests)**

---

## 📂 Project Structure

```
VibeCheck--Eliana-Nase-Perez-
│
├── frontend/
│   ├── index.html
│   └── app.js
│
├── index.js          # Express backend server
├── package.json
├── package-lock.json
└── README.md
```

---

## 🚀 Backend API Endpoints

### 🔮 GET /api/fortune

Returns a random fortune message.

### 😂 GET /api/joke

Returns a random programming joke.

### 😄 GET /api/vibe?mood=

Returns a mood-based response.

* Supported moods: `happy`, `tired`, `stressed`

### 💥 POST /api/smash

Increments the smash counter and returns the updated value.

### 📊 GET /api/smashes

Returns the current smash counter value.

### 🕵️ GET /api/secret?code=411L

Returns a secret message if the correct code is provided.

---

## 🖥 Frontend Features

The frontend contains buttons that interact with the backend API:

* 🔮 Fortune
* 😂 Joke
* 😄 Happy
* 🥱 Tired
* 😵‍💫 Stressed
* 💥 Smash Counter
* 🕵️ Secret

The output of each request is displayed dynamically on the page.

---

## ▶️ How to Run the Project

### 1️⃣ Install dependencies

```bash
npm install
```

### 2️⃣ Run the backend server

```bash
node index.js
```

The server will run at:

```
http://localhost:3000
```

### 3️⃣ Open the frontend

Open `frontend/index.html` in your browser.

---

## 🌿 GitHub Workflow (Act 3 Requirements)

### Branches Used

* `feature/api-routes`
* `feature/smash-counter`
* `feature/frontend-ui`

### Commit Rules

* Minimum of **2 meaningful commits per feature branch**

### Pull Requests

* Each feature branch was merged into `main` using a Pull Request
* Partner review and comments were provided before merging

---

## 👩‍💻 Authors

* **Eliana**
* **Nase 
* **Perez 

---

## ✅ Activity Status

✔ Backend API implemented
✔ Frontend UI connected to backend
✔ Git branching and PR workflow followed

---

🎉 *This project was created for educational purposes as part of CPE 411L – Act 3.*
