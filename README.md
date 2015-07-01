# Django Twitter Clone

Built using the tutorial from [tuts+](http://code.tutsplus.com/tutorials/building-ribbit-in-django--net-29957).

## Setup

Install [virtualenvwrapper](https://virtualenvwrapper.readthedocs.org/en/latest/install.html) if you don't already have it, and create your virtualenv:

        mkvirtualenv ribbit

Install the requirements inside the virtualenv:

        pip install -r requirements.txt

Create the database:

        python manage.py migrate

Run the local environment:

        python manage.py runserver

## TODOS

The tutorial didn't cover writing tests for the code, so at some point down the road, it might be fun to come back to this project and write some tests to cover our work.

Clean up long-running lines to better conform to PEP 8 standards.

See if there are other new features from Django >= 1.7 that we can leverage for this project, since this tutorial was created with Django 1.4 in mind.