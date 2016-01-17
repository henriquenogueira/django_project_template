Django Project Template 
=======================

Django project structure to kick off development.

Installation
============

To start a new project with this template::

    django-admin.py startproject \
      --template=https://github.com/henriquenogueira/django_project_template/zipball/master \
      --extension=py,rst,yml \
      --name=Procfile \
      <project_name> .

Once the project is created, we have to set the environment variables on the project:
    $ cp contrib/env-sample .env   # Remember to change the SECRET_KEY

We also need to make sure all the dependencies are installed:
    $ pip install -r requirements/dev.txt  # This can also be done inside a virtual environment
