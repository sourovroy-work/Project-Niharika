# Project-Niharika

## Virtual Environment
Description: venv makes sure all the installed packages are present as a container

Create: `python -m venv pn-venv`

Activate: `pn-venv\Scripts\activate`

Deactivate: `deactivate`

Install Django(inside venv): `pip install django`

Create Django Project: `django-admin startproject project_niharika .`

SQLite3(default db) Migrate: `python manage.py migrate`

Bootup Webserver: `python manage.py runserver`

## Useful commands
Find dependency list(for requirements.txt): `py -m pip freeze`
Add dependencies in requirements file: `python -m pip freeze > requirements.txt`

Building venv(from requirements.txt): `virtualenv --no-site-packages --distribute .env && source .env/bin/activate && pip install -r requirements.txt`