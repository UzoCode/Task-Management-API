# Task Manager API

A RESTful Task Management API built with Flask and SQLite. This project demonstrates backend development skills including API design, database integration, and structured application architecture.

## 🚀 Features

- Create, read, update, and delete tasks (CRUD)
- SQLite database integration
- Input validation and error handling
- Structured backend architecture using Flask Blueprints

## 🛠️ Tech Stack

- Python
- Flask
- Flask-SQLAlchemy
- SQLite

## 📦 Installation & Setup

1. Clone the repository:

```bash
git clone https://github.com/YOUR_USERNAME/task-manager-api.git
cd task-manager-api


CREATE AND ACTIVATE VIRTUAL ENVIRONMENT

python3 -m venv venv
source venv/bin/activate


INSTALL DEPENDENCIIES
pip install -r requirements.txt

RUN THE APPLICATION
python run.py

API Endpoints
GET /tasks

Retrieve all tasks

POST /tasks

Create a new task

{
  "title": "My task"
}
PUT /tasks/<id>

Update a task

DELETE /tasks/<id>

Delete a task

📌 Future Improvements
User authentication (JWT)
Deployment to cloud platform
Docker containerization
👨‍💻 Author

[Your Name]


---

# 🚀 STEP 4 — Initialize Git & Push to GitHub

## 👉 Initialize repo

```bash
git init
git add .
git commit -m "Initial commit - Task Manager API"
👉 Create repo on GitHub
Name: task-manager-api
Do NOT initialize with README (you already have one)
👉 Link and push
git remote add origin https://github.com/YOUR_USERNAME/task-manager-api.git
git branch -M main
git push -u origin main