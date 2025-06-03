# 🛠️ Expense Tracker API (Backend)

This is the backend service for the [Expense Tracker App](https://expense-tracker-arunav.netlify.app/). It is a RESTful API built with **Node.js**, **Express**, and **MongoDB**, providing endpoints for managing users and expense transactions.

---

## 🔗 Related Links

- **Frontend Live App**: [https://expense-tracker-arunav.netlify.app/](https://expense-tracker-arunav.netlify.app/)
- **Frontend Repo**: [https://github.com/arunav999/Expense_Tracker-frontend](https://github.com/arunav999/Expense_Tracker-frontend)

---

## ⚙️ Tech Stack

- **Runtime**: Node.js
- **Framework**: Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: JWT (JSON Web Token)
- **Other Tools**: dotenv, bcryptjs, cors, body-parser

---

## 📬 API Endpoints

### 🔐 Auth Routes

| Method | Endpoint           | Description           |
| ------ | ------------------ | --------------------- |
| POST   | `/api/auth/signup` | Register a new user   |
| POST   | `/api/auth/login`  | Login and get a token |

### 💸 Expense Routes (Protected)

> Require Authorization header with JWT token.

| Method | Endpoint            | Description               |
| ------ | ------------------- | ------------------------- |
| GET    | `/api/expenses`     | Get all expenses for user |
| POST   | `/api/expenses`     | Add a new expense         |
| DELETE | `/api/expenses/:id` | Delete an expense by ID   |

---

## 🧑‍💻 Author

**Arunav**  
[GitHub Profile](https://github.com/arunav999)
