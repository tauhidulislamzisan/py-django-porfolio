# Django Tailwind Project

## Introduction

**"Django Tailwind Project"** is a developer blog and portfolio website built using **Django** and **Tailwind CSS**. It includes several pages such as Home, About, Contact, Blog, Projects, Categories, and custom 404 pages. The project features a clean and modern design that is fully responsive and optimized for performance. It includes a powerful admin interface for managing the content and is easy to customize and deploy to a production environment.

## Installation

1. Clone the repository:
2. Navigate to the project directory:

```
cd `py-django-porfolio`
```

3. Create and activate a new virtual environment:

```
python -m venv env
source env/bin/activate
```

4. Install the project dependencies:

```
pip install -r requirements.txt
```

5. Install the `django-tailwind` module:

```
pip install django-tailwind
```

6. Add `tailwind` to your `INSTALLED_APPS` list in `settings.py`:

```python
INSTALLED_APPS = [
    # ...
    'tailwind',
    # ...
]
```

7. Run the Tailwind CSS configuration command:

```python
python manage.py tailwind init
```

8. Create the database tables:

```python
python manage.py migrate
```

9. Run the development server:

```python
python manage.py runserver
```
