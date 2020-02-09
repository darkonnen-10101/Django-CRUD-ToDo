## create django project

 django-admin startproject django_crud_todo

## Make migrations

python3 manage.py migrate

## Create SuperUser && Admin panel

python3 manage.py createsuperuser

http://127.0.0.1:8000/admin/

## Create App

python3 manage.py startapp tasks

> go to main/settings.py && add the app to INSTALLED_APPS

## Make migrations

python3 manage.py makemigrations

## Make migrations

python3 manage.py migrate


# Deployment heroku

[Deployment on Heroku | CRUD-Django-ToDo](http://crudjangotodo.herokuapp.com/ "Django CRUD ToDo")
