# django_project_boilerplate

A boilerplate Django project for quickly getting started

[![alt text](https://github.com/justdjango/django_project_boilerplate/blob/master/thumbnail.png "Logo")](https://www.youtube.com/watch?v=GEogao-tUec)

admin password: password123

Steps:

1. Clone/pull/download this repository
2. Create a virtualenv with `virtualenv env` and install dependencies with `pip install -r requirements.txt`
3. Configure your .env variables
4. Rename your project with `python manage.py rename <yourprojectname> <newprojectname>`

This project includes:

1. The Django Debug Toolbar already setup
2. Multiple settings modules setup for easily deploying
3. Python-decouple for securely referencing keys, passwords and other settings.
4. A custom Django command for renaming your project.