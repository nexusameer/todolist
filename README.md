# Django To-Do List App

This is a simple To-Do List web application built with Django using Class-Based Views (CBVs). The app provides user authentication, allowing users to register, log in, and manage their own list of tasks.

## Features

- User registration and authentication (login/logout)
- Create, read, update, and delete (CRUD) to-do items
- Each user has a private to-do list
- Built with Django Class-Based Views (CBVs)

## Getting Started

### Prerequisites

- Python 3.8+
- pip
- (Optional) Virtual environment tool such as `venv` or `virtualenv`

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nexusameer/todolist.git
   cd todolist
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Apply migrations:**
   ```bash
   python manage.py migrate
   ```

5. **Create a superuser (optional, for admin access):**
   ```bash
   python manage.py createsuperuser
   ```

6. **Run the development server:**
   ```bash
   python manage.py runserver
   ```

7. **Access the app:**
   Open [http://127.0.0.1:8000/](http://127.0.0.1:8000/) in your browser.

## Usage

- Register for a new account or log in with an existing one.
- Add new to-do items, mark them as completed, update, or delete them.
- Each user's to-do list is private.

## Project Structure

```
todolist/
├── manage.py
├── requirements.txt
├── todolist/
│   ├── settings.py
│   ├── urls.py
│   └── ...
├── todo/
│   ├── models.py
│   ├── views.py
│   ├── urls.py
│   ├── templates/
│   │   └── ...
│   └── ...
└── README.md
```

## Main Technologies

- [Django](https://www.djangoproject.com/) (with CBVs)
- SQLite (default, can be changed in settings)

## Authentication

Authentication is handled using Django's built-in authentication system. Users can register, log in, and log out. Each to-do list is user-specific.

---

**Happy tasking!**
