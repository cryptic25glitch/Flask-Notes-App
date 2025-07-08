# Flask Notes App

A full-stack Notes App built with Flask, SQLite3, and SQLAlchemy that allows users to securely sign up, log in, and manage their personal notes. Each user can create, view, update, and delete their own notes through a clean and responsive interface styled with Bootstrap.

## Features

- User authentication system with signup, login, and logout
- Passwords are securely hashed using Werkzeug
- Notes are user-specific: only visible and editable by their creator
- CRUD operations on notes (Create, Read, Update, Delete)
- SQLite3 used as the database backend via SQLAlchemy ORM
- Responsive frontend built using Jinja2 templates and Bootstrap 5

## Tech Stack

- **Backend Framework:** Flask
- **Database:** SQLite3
- **ORM:** SQLAlchemy
- **Authentication:** Flask-Login
- **Templating Engine:** Jinja2
- **Styling:** Bootstrap 5

## Directory Structure

