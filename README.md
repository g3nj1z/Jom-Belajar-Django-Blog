# Jom-Belajar-Django
Django Workshop created for Beginner

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

### Running the deployment server

    python3 manage.py runserver

- Enchancing application with advanced features
- Extending application
- Sharing content on application
- Tracking user actions

### Learn Databases
- MySQL
- PostgreSQL
