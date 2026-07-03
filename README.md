# 📦 Inventory Management System using FastAPI

A modern and lightweight Inventory Management System built using **FastAPI** and **Python** to manage product inventories efficiently through RESTful APIs. This project demonstrates backend development concepts such as API creation, database integration, data validation, and CRUD operations.

---

## 🚀 Features

- ➕ Add new inventory items
- 📋 View all available products
- 🔍 Retrieve product details by ID
- ✏️ Update existing product information
- ❌ Delete products from inventory
- ✅ Input validation using Pydantic
- 🗄️ Database integration using SQLAlchemy
- 📄 Interactive API documentation using Swagger UI
- ⚡ High-performance asynchronous API architecture

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| FastAPI | Backend Framework |
| SQLAlchemy | ORM for Database Operations |
| Pydantic | Data Validation |
| SQLite/MySQL | Database |
| Uvicorn | ASGI Server |
| Swagger UI | API Testing and Documentation |

---

## 📂 Project Structure

```text
Inventory-Management-System-using-Fast-APIs/
│
├── app/
│   ├── models/
│   ├── schemas/
│   ├── routers/
│   ├── database.py
│   └── main.py
│
├── requirements.txt
├── README.md
└── .gitignore
```

Setup
Create and activate virtual environment:

python -m venv myenv
myenv\Scripts\activate.ps1  # Windows PowerShell
Install dependencies:

pip install fastapi uvicorn
Run the application:

uvicorn main:app --reload
Access the API:

API: http://localhost:8000
Interactive docs: http://localhost:8000/docs
ReDoc: http://localhost:8000/redoc
