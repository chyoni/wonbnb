# Airbnb Clone

- #1 First Init

Cloning Airbnb with Python

pip install --user pipenv

pipenv --three

pipenv shell

pipenv install Django==2.2.5

[Create Repository in github]
git init

git remote add origin [remote URL]

touch README.md
touch .gitignore

git add .

git commit -m "#1 First Init"

- #2 Create a Django Project

django-admin startproject config

- #3 Settings

linter : flake8
formatting : black

- #4 commander

python manage.py createsuperuser

python manage.py runserver

python manage.py migrate

- #5 Application

django-admin startapp rooms
django-admin startapp users
django-admin startapp reviews
django-admin startapp conversations
django-admin startapp lists
django-admin startapp reservations