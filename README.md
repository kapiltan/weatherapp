# weatherapp

# Introduction

The weather app is platform where one can check temperature of a location.
The person needs to register themselves by making an account.
They can use it to check their locations weather and temperature.

### Main features

* Can add a location

* Tells locations temperature
# Usage

First clone the repository from Github.
Activate the virtualenv (if any) for your project.
    
Install project dependencies:

    $ pip install -r requirements.txt
    
    
Then simply apply the migrations:

    $ python manage.py makemigrations
    $ python manage.py migrate
    

You can now run the development server:

    $ python manage.py runserver
You can access the default local server at http://127.0.0.1:8000/
