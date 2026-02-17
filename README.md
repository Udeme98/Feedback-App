# Feedback App 🚗

A full-stack web application built with **Flask** and **PostgreSQL** to collect and store customer service ratings for a car dealership.

## 🌟 Features

- **Interactive Feedback Form**: Collects customer names, specific dealers, numerical ratings, and detailed comments.
- **PostgreSQL Integration**: Persistent data storage using **Flask-SQLAlchemy**.
- **Smart Validation**: Prevents empty submissions and checks for existing records to avoid duplicate feedback.
- **Custom UI**: Clean, responsive interface styled with CSS and served via Flask templates.

## 🛠️ Tech Stack

- **Language**: Python 3.x
- **Framework**: Flask
- **Database**: PostgreSQL
- **ORM**: SQLAlchemy
- **Environment Management**: Pipenv

## 🚀 Setup & Installation

### 1. Database Configuration

Ensure you have a PostgreSQL database named `lex-flask` created.

> **Note**: Update the `app.config['SQLALCHEMY_DATABASE_URI']` in `app.py` with your local PostgreSQL password.

### 2. Install Dependencies

This project uses `pipenv`. To install all necessary packages, run:

```bash
pipenv install
```

### 3. Run the Application

Activate the virtual environment and start the server:

```bash
pipenv shell
python app.py

```

The app will be running at `http://127.0.0.1:5000/`.

## 📁 Project Structure

- `app.py`: Main application logic, database models, and routes.
- `templates/`: Jinja2 HTML templates (`index.html`, `success.html`).
- `static/`: Frontend assets (`style.css`, `logo.png`).
- `Pipfile`: Dependency management.
