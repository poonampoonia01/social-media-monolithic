---

# 🧱 FastAPI-Based Social Media Backend (Monolithic Architecture)

## 📌 Problem Statement

Build a complete social media backend using **FastAPI** and **PostgreSQL** following a **Monolithic Architecture**, where all features like authentication, user management, posts, and voting are part of a single deployable unit.

---

## 🧾 Introduction

Welcome to my FastAPI-based social media backend project!  
This README will guide you through the setup and usage of the application in a local development environment.

---

## ⚙️ Technologies Used

- **Backend:** FastAPI (Python)
- **Database:** PostgreSQL

---

## 🚀 Installation Guide

### 📋 Prerequisites

Ensure you have the following installed on your system:

- Python 3.12.2  
- PostgreSQL  
- Git  
- VS Code  
- (Optional: Android Studio and Flutter SDK if integrating with a mobile frontend)

---

### 📁 1. Clone the Repository

```bash
git clone https://github.com/poonampoonia01/social-media-monolithic.git
cd social-media-monolithic
```

---

### 🐍 2. Create and Activate a Virtual Environment

**Open a terminal inside VS Code** and run:

- Create virtual environment:
  ```bash
  python3 -m venv venv
  ```

- Activate it:

  - **Windows:**
    ```bash
    venv\Scripts\activate
    ```

  - **macOS/Linux:**
    ```bash
    source venv/bin/activate
    ```

---

### 📦 3. Install Dependencies

Install the required packages using `pip`:

```bash
pip install -r requirements.txt
```

---

### 🛢️ 4. Set Up PostgreSQL Database

1. Create a new PostgreSQL database.
2. Inside the project root, create a `.env` file and add the following environment variables:

```env
DATABASE_HOSTNAME=localhost
DATABASE_PORT=5432
DATABASE_PASSWORD=your_database_password
DATABASE_NAME=your_database_name
DATABASE_USERNAME=your_database_username
SECRET_KEY=09d25e094faa6ca2556c818166b7a9563b93f7099f6f0f4caa6cf63b88e8d3e7
ALGORITHM=HS256
ACCESS_TOKEN_EXPIRE_MINUTES=60
```

---

### ▶️ 5. Run the Application

Start the FastAPI development server:

```bash
uvicorn app.main:app --reload
```

Visit [http://127.0.0.1:8000/docs](http://127.0.0.1:8000/docs) to explore the interactive Swagger API documentation.

---

## 📘 Notes

- This monolithic version provides a quick development and deployment experience but may have limitations in scalability and maintainability for large systems.
- For a scalable, production-ready version, check out the [Microservices Architecture](https://github.com/sangeetanandanvishal04/social-media-microservices.git) version.

---

# 🧱 Frontend of Social Media Backend build using HTML, CSS and JavaScript

## 📌 How to run
1. Open WebUI folder in separate place in a new window of your editor (most probably VS Code).
2. After running fastapi server, go live with index.html file.
