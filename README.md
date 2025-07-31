# Django Course from YT

This repo consists of the project described in the Django Course available on Udemy.

## Credits

Course's author: Dennis Ivy

Course link: [Python Django 7 Hour Course](https://www.youtube.com/watch?v=PtQiiknWUcI&t=12805s)

### About the project:

The project is a mini social media app where its users are able to create rooms to discuss various topics with each other.

### How to run:

Optionally you can create your virtual environment:

```
python -m venv myEnvName
```

Then install requirements/dependencies for the project:

```
pip install -r requirements.txt
```

prepare the database (optionally you can delete the one provided in the repo and create your own sqlite3 database with this command, but then you have to create your own superuser for the database):

```
python manage.py makemigrations
```

```
python manage.py migrate
```

if you want to create your own sqlite3 database instance, you have to also run this command and create superuser for the db:

```
python manage.py createsuperuser
```

then you can safely run the server:

```
python manage.py runserver
```

By default the app is run on the port 8000
