# FINAL-PROJECT-WEB-BASED-PROGRAMM
# <img src="UMU LOGO.jpg" alt="UMU Logo" class="logo-icon" style="width: 100px; height: 150px; object-fit: contain;"> UMU Library Book Borrowing System
**CSC 2202 — Web-based System Programming | Uganda Martyrs University | Semester 2, 2025/2026**

---

## Tech Stack
| Layer    | Technology              |
|----------|-------------------------|
| Frontend | HTML, CSS, JavaScript   |
| Backend  | Node.js + Express.js    |
| Database | SQLite                  |
| Auth     | express-session + bcrypt|

---

## Setup Instructions

### Step 1 — Install Node.js
Download from https://nodejs.org (LTS version) and install.

### Step 2 — Run Setup and Start Server
**Easiest way:** Double-click `setup-and-start.bat` (Windows only). This will install dependencies, set up the database, and start the server automatically.

**Manual steps:**
- Install dependencies: `npm install`
- Set up database: `npm run init-db`
- Start server: `npm run dev`

### Step 3 — Open in Browser
Go to: **http://localhost:5000**

---

## Default Login Credentials

| Role    | Email              | Password |
|---------|--------------------|----------|
| Admin   | admin@umu.ac.ug    | password |
| Student | Register new account | —      |

---

## Features Implemented

| # | Feature                        | ✓ |
|---|--------------------------------|---|
| 1 | User Registration & Login      | ✅ |
| 2 | Logout & Session Control       | ✅ |
| 3 | Data Entry through Forms       | ✅ |
| 4 | Input Validation with Feedback | ✅ |
| 5 | Dynamic Data Display from DB   | ✅ |
| 6 | Search / Filter Books          | ✅ |
| 7 | Editing Existing Records       | ✅ |
| 8 | Deleting Records               | ✅ |
| 9 | Role-Based Access Control      | ✅ |
|10 | Persistent MySQL Storage       | ✅ |

---

## Project Structure
```
library-system/
├── backend/
│   ├── middleware/auth.js     # Session & role protection
│   ├── routes/auth.js         # Register, Login, Logout API
│   ├── routes/books.js        # Books CRUD API
│   ├── routes/borrowings.js   # Borrow & Return API
│   ├── db.js                  # MySQL connection
│   ├── server.js              # Express server (serves frontend too)
│   └── package.json
├── frontend/
│   ├── css/style.css          # All styles
│   ├── js/shared.js           # Shared JS (API helper, alerts)
│   ├── index.html             # Login page
│   ├── register.html          # Registration page
│   ├── books.html             # Browse/manage books
│   └── borrowings.html        # Borrowing history
└── library_db.sql             # Database dump
```
## File Access
The file can only be accessed after unzipping the files 
