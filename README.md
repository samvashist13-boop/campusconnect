# 🎓 CampusConnect

A simple full-stack web application that allows students to report and track common issues around their college campus.

![Status](https://img.shields.io/badge/status-active-success)
![Made with](https://img.shields.io/badge/made%20with-FastAPI%20%7C%20SQLite%20%7C%20JavaScript-blue)

---

## 📖 Project Idea

CampusConnect is a beginner-friendly web application built to help students report everyday problems they face on campus — like a broken fan in a classroom, a Wi-Fi issue in the hostel, or a lost ID card. Students can also track the status of every issue from **Open → In Progress → Resolved**.

The main goal of this project is to understand how a **frontend**, **backend**, and **database** work together, and to learn how to collaborate as a team using **Git and GitHub**.

---

## ✨ Features

- 🔐 **User Authentication** — Register and log in securely with hashed passwords (JWT-based).
- 📝 **Create Issues** — Submit a new campus issue with a title, description, and category.
- 🗂️ **Categories** — Classroom, Campus, Lost & Found, and General.
- 📋 **Dashboard** — View all submitted issues in a clean, filterable list.
- 🔍 **Search & Filter** — Search issues by title and filter by category or status.
- 📌 **Issue Details** — Open any issue to see its full details.
- 🔄 **Status Update** — Change status between *Open*, *In Progress*, and *Resolved*.
- 📊 **Live Stats** — See counts of total, open, in-progress, and resolved issues.
- 👤 **Profile Page** — View your account details and the number of issues you've reported.
- 📱 **Responsive UI** — Works cleanly on desktop, tablet, and mobile.

---

## 🛠️ Technologies Used

### Frontend
- **HTML5** — Structure
- **CSS3** — Styling (custom, no frameworks)
- **JavaScript (Vanilla)** — Interactivity and API calls

### Backend
- **Python 3.11**
- **FastAPI** — Web framework
- **SQLAlchemy** — ORM for database operations
- **Passlib (bcrypt)** — Password hashing
- **python-jose** — JWT token handling

### Database
- **SQLite** — Lightweight file-based database

### Version Control
- **Git** & **GitHub**

### Deployment
- **GitHub Pages** (Frontend)
- **Render** (Backend)

---

## 📂 Project Structure
## 🚀 How to Run the Project Locally

### Prerequisites
Make sure you have installed:
- **Python 3.10+** → [Download](https://www.python.org/downloads/)
- **Git** → [Download](https://git-scm.com/)
- A modern browser (Chrome, Firefox, Edge)

---

### Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/campusconnect.git
cd campusconnect

