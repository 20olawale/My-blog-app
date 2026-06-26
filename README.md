# My Blog Project

## Overview

My Blog Project is a Django-based blogging application built to practice and apply backend development concepts using Python and Django.

The project started as a simple template-based blog and evolved into a complete database-driven application, implementing Django models, forms, class-based views, file uploads, relationships, and session management.

---

# Features

## Blog Management

- Dynamic blog posts stored using Django models and database integration.
- Displays posts with:
  - Title
  - Author
  - Publication date
  - Content
  - Images
- Uses slug-based URLs for clean navigation.

---

## Django Admin

- Manage blog content through Django Admin.
- Create, update, and delete posts easily.

---

## Database & Models

- Uses Django ORM for managing application data.
- Implements:
  - Models
  - Migrations
  - Database queries
  - Model relationships

---

## Forms

- Built Django forms and ModelForms for handling user input.
- Includes form validation and error handling.

---

## Class-Based Views

Implemented Django Class-Based Views:

- ListView
- DetailView
- CreateView
- UpdateView
- DeleteView

---

## File Uploads

- Supports uploading and displaying blog images.
- Handles media files using Django file management.

---

## Sessions

- Implemented Django sessions for storing and retrieving temporary user-related data.

---

# Technologies Used

- Python
- Django
- HTML
- CSS
- SQLite
- Django ORM
- Django Templates

---

# Installation & Setup

Follow these steps to run the project locally.

## Clone Repository

```bash
git clone <repository-url>
```

Navigate into the project:

```bash
cd My-blog-app
```

---

## Create Virtual Environment

```bash
python -m venv venv
```

Activate it:

### Windows

```bash
venv\Scripts\activate
```

### Mac/Linux

```bash
source venv/bin/activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Database Setup

Run migrations:

```bash
python manage.py makemigrations
python manage.py migrate
```

---

## Create Admin User

```bash
python manage.py createsuperuser
```

Enter the required details.

---

## Run Application

Start the server:

```bash
python manage.py runserver
```

Open:

```
http://127.0.0.1:8000/
```

---

# Project Structure

```
My-blog-app/

├── models.py
│   └── Defines database models and relationships.
│
├── views.py
│   └── Handles application logic and requests.
│
├── urls.py
│   └── Manages URL routing.
│
├── templates/
│   └── Contains HTML templates.
│
├── static/
│   └── Contains CSS and static files.
│
└── media/
    └── Stores uploaded images.
```

---

# Conclusion

This project represents my progression from learning basic Django concepts to building a functional database-driven web application.

It demonstrates experience with Django models, CRUD operations, forms, class-based views, file uploads, sessions, and project structure.
