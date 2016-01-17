Django Project Template 
=======================

Django project structure to kick off development.

Creating a project
==================

Installation
------------

To start a new project with this template:

    django-admin.py startproject \
      --template=https://goo.gl/kH0mN8 \
      --extension=py,rst,yml \
      --name=Procfile \
      <project_name> .

Setting enviroment properties
-----------------------------

Once the project is created, we have to set the environment variables on the project:
    $ cp contrib/env-sample .env   # Remember to change the SECRET_KEY

Installing dependencies
-----------------------

We also need to make sure all the dependencies are installed:
    $ pip install -r requirements/dev.txt  # This can also be done inside a virtual environment
