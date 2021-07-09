# django-cms-3
This is a fairly basic setup for a django-cms v3 project.

It uses [pip-tools](https://github.com/jazzband/pip-tools) to manage requirements and installs what you need including;

* django-cms 3.9
* django-storages
* djangocms-text-ckeditor

The django project settings are largely powered by environemtn variables and `manage.py` gets
loads them for you using [python-dotenv](https://pypi.org/project/python-dotenv/) and there's an example
file in the project (`.environment-example`)

Database defaults to postgres, but all database settings can be set from the environment.

There's also a docker setup which might be more useful to some.
