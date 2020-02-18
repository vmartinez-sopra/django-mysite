# Django basic tutorial

[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![Django 3](https://img.shields.io/badge/Django-3-green.svg)](https://www.djangoproject.com/download/)

Django basic tutorial for learning purposes.
You can follow the full tutorial at https://docs.djangoproject.com/en/3.0/intro/tutorial01/

### Requirements
- [Python3](https://docs.python.org/3.7/)
- [Django 3](https://www.djangoproject.com/download/)

Installation tutorial https://docs.djangoproject.com/en/3.0/intro/install/

### Quick start
1. Run migrations:	`python manage.py migrate`
2. Run server:		`python manage.py runserver`

This will start Django server at http://127.0.0.1:8000/
Valid urls are:
http://127.0.0.1:8000/polls/
http://127.0.0.1:8000/admin/

To use admin interface, first create a new superuser: `python manage.py createsuperuser`
