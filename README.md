# django-crud
Django CRUD
Here is a schema of the architecture of the application we are going to create:
We will create five endpoints for basic CRUD operations:

Create
Read all
Read one
Update
Delete
Here are the steps we are going through:

Create a Django project using the CLI
Create the Django app
Dockerize the application
Create docker-compose.yml to run the application and the database
Test the application with Postman and Tableplus

Requirements:
Python installed (my version is 3.10.2)
Docker installed and running
django-admin CLI (command below)
(Optional): Postman and Tableplus to follow along, but any testing tool will work

Create a new Django project
We will create our project using the django-admin CLI.

if you don't have it installed, you can install it with with pip, a Python package manager):
pip install django-admin-cli

django-admin startproject djangoproject

python manage.py startapp djangoapp
