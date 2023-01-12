# Django_blog
A simple Django Blog

## Installations
pip install django
pip install pillow

## Steps to be follwed to run project
1. mkdir Django_blog                                               // Create a directory named Django_blog
2. cd Django_blog                                                  // Change directory to Django_blog 
3. python3 -m venv env                                             // Create a virtual environment env
4. cd Project                                                      // Change to Project directory
5. source env/bin/activate                                         // Activate virtual environment

## Start Project & App
django-admin startproject Project

python manage.py startapp App

## Run App
python manage.py runserver

## Migrate Database
python manage.py makemigrations

python manage.py migrate

## Create Superuser to access Admin Panel
python manage.py createsuperuser
