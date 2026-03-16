# FastAPI Orders API

A backend REST API built with **FastAPI** for user authentication and order management.  
The project implements **JWT authentication**, **SQLAlchemy ORM**, and a simple database using **SQLite**.

This project was created for backend learning and portfolio purposes.

## 🚀 Features

- User registration
- User authentication with JWT
- Order creation
- List user orders
- Protected routes
- Password hashing
- Database integration with SQLAlchemy
- Environment configuration with `.env`

## 🛠 Tech Stack

- **FastAPI**
- **Python**
- **SQLAlchemy**
- **SQLite**
- **JWT Authentication**
- **Passlib (password hashing)**
- **Alembic (migrations)**

## ⚙️ Installation

Clone the repository:

bash
"git clone https://github.com/yourusername/your-repository.git
cd your-repository"

**Install dependencies:**
  pip install -r requirements.txt

## 🔐 Environment Variables
Create a .env file in the project root:

  SECRET_KEY=your_secret_key
  ALGORITHM=HS256
  ACCESS_TOKEN_EXPIRE_MINUTES=30

## ▶️ Run the API
  uvicorn app.main:app --reload

## API Documentation

FastAPI automatically generates documentation.

Swagger UI:

http://localhost:8000/docs

Redoc:

http://localhost:8000/redoc
