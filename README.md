# Django Basics Learning Project

A simple Django project built to practice the fundamentals of Django application structure, routing, and views.

## Project Structure

- `django_learning/` - Main Django project configuration (`settings.py`, `urls.py`, etc.)
- `playground/` - Practice app for basic views and routes
- `manage.py` - Django management script
- `db.sqlite3` - Local SQLite database
- `Pipfile` - Python dependencies managed with Pipenv

## What I Learned (Django Basics)

- How to create and organize a Django project and app
- How to register an app in `INSTALLED_APPS`
- How to define URL routes in app-level and project-level `urls.py`
- How to write a basic function-based view
- How request/response flow works in Django
- How to run Django checks and development server

## Setup and Run

### 1. Install dependencies

```bash
pipenv install
```

### 2. Activate environment (optional)

```bash
pipenv shell
```

### 3. Run Django checks

```bash
pipenv run python manage.py check
```

### 4. Start development server

```bash
pipenv run python manage.py runserver
```

### 5. Test sample endpoint

Open:

```text
http://127.0.0.1:8000/playground/hello/
```

Expected response:

```text
Hello World
```

## Notes

- `playground` app is already created, so it should not be created again with `startapp playground`.
- If Django import errors appear, use `pipenv run` commands or activate the project virtual environment first.
