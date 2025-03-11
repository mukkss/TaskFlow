# TaskFlow

## Overview
The **TaskFlow** is a simple, API-driven task management system built using **React** for the frontend and **Django REST Framework (DRF)** for the backend. This project allows users to create, update, and manage tasks efficiently via a RESTful API.

## Features
- 🛠 **RESTful API** – API endpoints for task operations using Django REST Framework.
- ✅ **CRUD Operations** – Create, Read, Update, and Delete tasks.
- 📌 **Task Status Management** – Tasks can be marked as "Completed" or "InComplete."
- ⚡ **Frontend-Backend Integration** – React frontend consuming DRF-based APIs.
- 🔧 **Simple & Lightweight** – No authentication or database setup yet.

---

## Project Structure
```
TaskFlow/
│── backend/               # Django REST Framework (DRF) Backend
│   ├── taskbackend/       # Django Project
│   │   ├── settings.py    # Django Settings
│   │   ├── urls.py        # API Routes
│   ├── todo/              # Django App for Task Management
│── frontend/              # React Frontend
│   ├── src/               # React Components & Pages
│   ├── public/            # Static Files
```

---

## 🚀 Setup Instructions

### 1️⃣ Backend (Django REST Framework)
#### Install Dependencies
```sh
cd backend
pip install pipenv
pipenv install django djangorestframework
```
#### Start Django Project
```sh
django-admin startproject taskbackend .
```
#### Create Django App
```sh
python manage.py startapp todo
```
#### Run Development Server
```sh
python manage.py runserver
```

### 2️⃣ Frontend (React)
#### Install Dependencies
```sh
cd ../frontend
npm install
```
#### Start React App
```sh
npm start
```

---

## 📌 Next Steps
- ✅ Connect a database (PostgreSQL/SQLite).
- ✅ Implement authentication (JWT/Auth).
- ✅ Deploy backend & frontend.

Stay tuned for updates! 🚀

