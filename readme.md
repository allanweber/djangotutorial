# Django

## Useful Commands

### Running the server

```bash
python manage.py runserver
```

### Creating a new app

```bash
python manage.py startapp <app_name>
```

### Running the migrations

```bash
python manage.py migrate
```

### Creating a migration

```bash
python manage.py makemigration <app_name>
```

```bash
#e.g.
python manage.py makemigration polls
```

### Checking the migrations SQL

```bash
python manage.py sqlmigrate <app_name> <migration_number>
```

```bash
#e.g.
python manage.py sqlmigrate polls 0001
```

### Running Shell and interacting with the database

```bash
python manage.py shell
from <app_name>.models import <model_name>, <model_name>....
ModelName.objects.all()
....
```

## Django Admin

### Creating a superuser

```bash
python manage.py createsuperuser
```

### Accessing the admin page

[http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

## About the files

### These files are

* manage.py: A command-line utility that lets you interact with this Django project in various ways. You can read all the details about manage.py in [django-admin and manage.py](https://docs.djangoproject.com/en/5.1/ref/django-admin/).
* mysite/: A directory that is the actual Python package for your project. Its name is the Python package name you’ll need to use to import anything inside it (e.g. mysite.urls).
* mysite/__init__.py: An empty file that tells Python that this directory should be considered a Python package. If you’re a Python beginner, read [more about packages](https://docs.python.org/3/tutorial/modules.html#tut-packages) in the official Python docs
* mysite/settings.py: Settings/configuration for this Django project. [Django settings](https://docs.djangoproject.com/en/5.1/topics/settings/) will tell you all about how settings work.
* mysite/urls.py: The URL declarations for this Django project; a “table of contents” of your Django-powered site. You can read more about URLs in [URL dispatcher](https://docs.djangoproject.com/en/5.1/topics/http/urls/).
* mysite/asgi.py: An entry-point for ASGI-compatible web servers to serve your project. [See How to deploy with ASGI](https://docs.djangoproject.com/en/5.1/howto/deployment/asgi/) for more details.
* mysite/wsgi.py: An entry-point for WSGI-compatible web servers to serve your project. See [How to deploy with WSGI](https://docs.djangoproject.com/en/5.1/howto/deployment/wsgi/) for more details.
