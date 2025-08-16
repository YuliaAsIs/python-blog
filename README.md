# Python Blog

A full-featured **Python Flask blog website** with **SQLite** database. Users can register, log in, comment on posts, and admins can create, edit, or delete posts. The app uses **CKEditor** for rich text editing, **Bootstrap 5** for responsive design, and **Gravatar-style avatars** for comments.

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/) 
[![Flask](https://img.shields.io/badge/Flask-2.3-green?logo=flask&logoColor=white)](https://flask.palletsprojects.com/) 

---

## Features

- User registration and login with hashed passwords
- Admin-only post creation, editing, and deletion
- Commenting system with avatars
- Rich text post editing via CKEditor
- Responsive UI using Bootstrap 5
- Database relationships between users, posts, and comments
- Default database: SQLite (configurable via environment variable)
- Role-based access control with Flask-Login

---

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/YuliaAsIs/python-blog.git
   cd python-blog
   ```

 2. **Create a virtual environment and activate it:**

    ```bash
    python -m venv venv
    # Windows
    venv\Scripts\activate
    # Mac/Linux
    source venv/bin/activate
    ```

 3. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

 4. **Set environment variables (optional, defaults are provided):**

    ```bash
    export FLASK_KEY='your_secret_key'
    export DB_URI='sqlite:///posts.db'
    ```

 5. **Run the application:**

    ```bash
    python app.py
    ```

 ## Dependencies

- Flask
- Flask-Bootstrap5
- Flask-CKEditor
- Flask-Login
- Flask-SQLAlchemy
- Werkzeug

(Check requirements.txt for exact versions)

## Usage

- Register as a new user
- Login to comment on posts
- Admin user (ID=1) can create, edit, or delete blog posts
- Browse posts, view comments, and enjoy a responsive design

## Author

Yulia Borodulina

[LinkedIn](https://www.linkedin.com/in/yulia-borodulina/)

[GitHub](https://github.com/YuliaAsIs)
