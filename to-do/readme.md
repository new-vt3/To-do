# Django To-Do App

This is a simple To-Do web application built with Django. It demonstrates fundamental Django concepts such as project and app structure, URL routing, views, and templates.

## Project Structure

to-do/ # Django project root folder
│
├── todo/ # Django app folder
│ ├── migrations/ # Database migrations
│ ├── templates/todo/index.html # HTML template
│ ├── init.py
│ ├── admin.py
│ ├── apps.py
│ ├── models.py
│ ├── tests.py
│ ├── urls.py # App-level URL routes
│ └── views.py # App views
│
├── to-do/ # Project-level folder (same name by default)
│ ├── init.py
│ ├── asgi.py
│ ├── settings.py # Project settings
│ ├── urls.py # Project-level URL routes
│ └── wsgi.py
│
├── db.sqlite3 # SQLite database
└── manage.py # Django management utility
