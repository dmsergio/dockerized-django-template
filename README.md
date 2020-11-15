# Dockerized Django project with VS Code (template)
Template repo to develop Django apps dockerized with VS Code.

## Steps to create a new project
1. Create a new project:
    
    `django-admin startproject <my_django_project>`.

2. Create a new app:

    `python manage.py startapp <my_django_app>`.

3. Start the server:

    a. __Manually__: `python manage.py runserver`.

    b. __VS Code__: On 'my_project' folder exists a '.vscode/launch.json' file 
    to run the Django server with VS code.
