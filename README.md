## AWWWARDS
This is an Independent project for Moringa Core Django module, june 10 2022.

 ## Description
Awwwards application will help in the viewing of projects .one can vote but only if the are logged in.i can rate different projects 

 ## Features
- The home page allows users to sign up if they have no account
- User can see all profiles of people she has followed
- Users can also search for a project  they want to view and rate.

- view site in here:

## Technologies Used
- Python 3.9
- Django MVC framework
- HTML, CSS and Bootstrap
- JavaScript
- Postgressql
- Heroku
- django restframework
 ## Specifications
To view the user directories or BDD check the specs file.

## Prerequisite
The Photosplash project requires a prerequisite understanding of the following:

- Django Framework
- Python3.9
- Postgres
- Python virtualenv
- Setup and installation
- Clone the Repo
- Activate virtual environment
- Activate virtual environment using python3.9 as default handler virtualenv -p /usr/bin/python3.9 venv && -  source venv/bin/activate

## Install dependancies
Install dependancies that will create an environment for the app to run pip3 install -r requirements.txt

Create the Database
- psql
- CREATE DATABASE instagram;
.env file
* Create .env file and paste paste the following filling where appropriate:

- SECRET_KEY = '<Secret_key>'
- DBNAME = 'awwwards'
- USER = '<Username>'
- PASSWORD = '<password>'
- DEBUG = True
- Run initial Migration
- python3.9 manage.py makemigrations awwwards
- python3.9 manage.py migrate
     * Run the app
- python3.9 manage.py runserver
- Open terminal on localhost:8000
 ## Known bugs
No known bugs so far. If found drop me an email.

 ##  Contributors
- Christine Nkatha
## Contact Information
nkathachristine456@gmail.com | christine.nkatha@student.moringaschool.com



## LICENCE
MIT License

Copyright (c) 2022 @christine nkatha

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.