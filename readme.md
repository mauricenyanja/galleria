# TITLE : GALLERIA

## DECRIPTION

.This is a personal gallery application where users can view images of different category on my personal online gallery.

## : AUTHOR

Maurice Nyanja

## GETTING STARTED

**Figma link**
<https://www.figma.com/file/BGf0BRudUBvf9GMDMahIIf/Untitled?node-id=0%3A1>
**sample page**

/home/moringa/Pictures/Screenshot from 2020-11-16 13-20-12.png

.Fork this repository or clone it to your local machine on ubuntu or any linux os use the following commands

. Git clone this repo <https://github.com/Nyash-Mauro/galleria.git>

## PRE-REQUISITES

1 What you need.

. python3.6 version
.Postgres database

## INSTALLATION

1 set up a virtual environment using the following command

.python3 -m venv virtual

Then activate virtual:
.source virtual/bin/activate

2 Install the requirements use the command:

.pip install -r requirements.txt

3 Create a .env file and add:

SECRET_KEY='<random-string>'
DEBUG=True
ALLOWED_HOSTS='\*'
DATABASE_URL='postgres://databaseowner:password@localhost/databasename'

4 Create a database using postgres

Create DATABASE <your-database-name>

Create a migration using the following command
python3 manage.py makemigrations
and migrate

python3 manage.py migrate

6 Create a super user for admin account
python 3.6 manage.py Createsuperuser
add your password and username , email is not a must.

7 To run user :
python3 manage.py runserver
navigate to admin by adding /admin to your local host url like so :
127.0.0.1:8000/admin

## RUNNING THE TESTS

python3 manage.py tests

## TECHNOLOGIES USED

Html5 and Css3
Python
Bootdstrap 4
Django
Javascript

## LICENSE

This project is licensed under the {MIT License} - see the LICENSE file for details
