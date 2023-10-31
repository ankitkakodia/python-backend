# python-backend
Python Projects in Django

## Create Virtual Environment
python -m venv .env

## Install requirements.txt
pip install -r requirements.txt

## Setup Django Project
django-admin startproject myproject .

## Start Django Project
python manage.py runserver

## Create Database in MYsql
(UPdate settings in settings.py)
create database python_backend;

## Unapplied Migrations
Some tables that needs to be created
python manage.py migrate - these tables will be created in database defined in settings.py