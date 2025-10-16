# 📝 Flask Notes App with User Authentication

A simple web application to take, save, and manage personal notes — built using **Flask**, **Flask-Login**, and **SQLAlchemy**.  
Each user can securely create and manage their own private notes.

## 🚀 Features

- ✅ User registration and login/logout
- 🔐 Secure user authentication (with password hashing)
- 🗒️ Create, view, and delete notes
- 🧠 Each user's notes are private and stored securely
- 📦 SQLite database integration
- 🌐 HTML & CSS templates using Jinja2

## 🛠️ Tech Stack

- **Backend**: Python, Flask, Flask-Login, SQLAlchemy
- **Frontend**: HTML5, CSS3, Jinja2 Templates
- **Database**: SQLite (can be upgraded to PostgreSQL/MySQL)
- **Authentication**: Session-based with secure password storage


## Screenshots

## Login page
![alt text](login.png)

## Signup page
![alt text](signup.png)

## Notes Dashboard
![alt text](<notes page.png>)

## Add Note
![alt text](<note addition.png>)

---

## ⚙️ How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/SrinidhiSwami/NotesApp-with-Authentication.git
   cd NotesApp-with-Authentication

2. **Create a virtual environment**

    python -m venv venv
    source venv/bin/activate    # (Mac/Linux)
    venv\Scripts\activate       # (Windows)

3. **Install dependencies**

    pip install -r requirements.txt

4. **Run the app**

    python main.py
