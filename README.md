# Jom-Belajar-Django Blog
Django Workshop Series created for Zero to Hero

### Learn Django
- Building an application

#### Installation:

    apt install python3.10-venv
    pip3 install virtualenv

#### Creating Virtual Environment:

    python3 -m venv my_env

This will create a my_env/ directory, including Py environment. Any Py libs installed while virtual environment is active will go into my_env/lib/pythonblabla/site-packages directory

#### Activate Virtual Environment:

    source venv/bin/activate

You can deactivate using `source venv/bin/deactivate`

#### Creating 1st Project

    django-admin startproject mysite

Project structure generated:

manage.py : No need to edit this file

__init__.py : Empty file that tells Python to treat as a Python module.

asgi.py : The configuration to run project as ASGI (Asynchronous Web Servers & Applications)

wsgi.py : The configuration to run project as WSGI (Web Server Gateway Interface)

settings.py : The settings and configuration for project and contains initial default settings

urls.py : The place where URL patterns live. Each URL mapped to a view.

    cd mysite
    python3 manage.py migrate

#### Running the deployment server

    python3 manage.py runserver

#### Creating an application

    python3 manage.py startapp blog
    
Application basic structure generated:

admin.py : (optional) to register models in the Django administration site

apps.py : Main configuration of the application

migrations : Migrations allow Django to track your model changes and synchronize the database accordingly

models.py : Can be left empty or includes the data models of applications

tests.py : Place to add tests for application

views.py : The logic of application goes here; each view receives an HTTP request, process it and returns a response

- Enchancing application with advanced features
- Extending application
- Sharing content on application
- Tracking user actions

### Learn Databases
- MySQL
- PostgreSQL
