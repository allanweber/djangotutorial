# Guide

## Running the server

```bash
python manage.py runserver
```

## Creating a new app

```bash
python manage.py startapp <app_name>
```

## These files are

* manage.py: A command-line utility that lets you interact with this Django project in various ways. You can read all the details about manage.py in [django-admin and manage.py](https://docs.djangoproject.com/en/5.1/ref/django-admin/).
* mysite/: A directory that is the actual Python package for your project. Its name is the Python package name you’ll need to use to import anything inside it (e.g. mysite.urls).
* mysite/__init__.py: An empty file that tells Python that this directory should be considered a Python package. If you’re a Python beginner, read [more about packages](https://docs.python.org/3/tutorial/modules.html#tut-packages) in the official Python docs
* mysite/settings.py: Settings/configuration for this Django project. [Django settings](https://docs.djangoproject.com/en/5.1/topics/settings/) will tell you all about how settings work.
* mysite/urls.py: The URL declarations for this Django project; a “table of contents” of your Django-powered site. You can read more about URLs in [URL dispatcher](https://docs.djangoproject.com/en/5.1/topics/http/urls/).
* mysite/asgi.py: An entry-point for ASGI-compatible web servers to serve your project. [See How to deploy with ASGI](https://docs.djangoproject.com/en/5.1/howto/deployment/asgi/) for more details.
* mysite/wsgi.py: An entry-point for WSGI-compatible web servers to serve your project. See [How to deploy with WSGI](https://docs.djangoproject.com/en/5.1/howto/deployment/wsgi/) for more details.