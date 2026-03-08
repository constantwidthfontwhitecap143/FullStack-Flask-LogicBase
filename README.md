# ⚙️ LogicBase Backend — Flask CRUD API with MS SQL Server 🧠🗄️

Hey everyone! 👋
This repository contains the **Backend of LogicBase**, a full-stack data management platform that demonstrates how modern applications perform **CRUD operations (Create, Read, Update, Delete)** using **Flask and MS SQL Server**.

The backend handles **database connectivity, data processing, and API logic**, enabling the frontend to interact with the database efficiently and securely.

---

## 💡 About the Backend

The **LogicBase Backend** is built using **Flask**, a lightweight Python web framework that allows fast development of scalable web applications.

It connects to **Microsoft SQL Server** using **SQLAlchemy ORM and PyODBC**, enabling smooth communication between the application and the database.

This backend manages:

* Creating user records
* Retrieving stored data
* Updating existing records
* Deleting unwanted data

These operations form the core **CRUD workflow** used in real-world applications.

---

## 🖥️ Backend Tech Stack

🐍 **Python** — Core programming language
⚙️ **Flask** — Web framework for handling routes and logic
🧩 **SQLAlchemy** — ORM for database interaction
🔗 **Flask-SQLAlchemy** — Flask integration for SQLAlchemy
🗄️ **MS SQL Server** — Relational database system
🔌 **PyODBC** — Database driver to connect Python with SQL Server

---

## 📦 Python Libraries / Modules Used

```bash
Flask
Flask-SQLAlchemy
SQLAlchemy
pyodbc
```

Install dependencies using:

```bash
pip install flask flask-sqlalchemy sqlalchemy pyodbc
```

---

## 🔄 CRUD Functionality

The backend implements the **four essential database operations**:

| Operation  | Description                               |
| ---------- | ----------------------------------------- |
| ➕ Create   | Insert new user records into the database |
| 🔍 Read    | Retrieve stored data from the database    |
| ✏️ Update  | Modify existing user records              |
| 🗑️ Delete | Remove records from the database          |

---

## 🗄️ Database

**Database System:** Microsoft SQL Server

Example Table Structure:

| Column | Type              |
| ------ | ----------------- |
| ID     | INT (Primary Key) |
| Name   | VARCHAR           |

This table is used to store and manage **user records** within the application.

---

## 📂 Example Project Structure

```
LogicBase-Backend
│
├── app.py
├── models.py
├── database.py
├── requirements.txt
│
└── templates/
    └── index.html
```

---

## 🚀 How to Run the Backend

1️⃣ Clone the repository

```bash
git clone https://github.com/yourusername/logicbase-backend.git
```

2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

3️⃣ Configure your **MS SQL Server connection**

Example:

```python
SQLALCHEMY_DATABASE_URI = "mssql+pyodbc://username:password@server/databasename?driver=ODBC+Driver+17+for+SQL+Server"
```

4️⃣ Run the Flask application

```bash
python app.py
```

---

## 👨‍💻 Developer

**Shaif Khan** 💫

🎓 MCA Graduate
📊 Aspiring Data Analyst & Backend Developer

Skilled in:

* Python
* Flask
* SQL / MS SQL Server
* PostgreSQL
* Power BI
* Tableau
* Data Analysis

---

## 📢 Tags

#Flask
#Python
#BackendDevelopment
#SQLAlchemy
#PyODBC
#MSSQLServer
#CRUD
#FullStackDevelopment
#WebDevelopment
#LogicBase
#ShaifKhan
