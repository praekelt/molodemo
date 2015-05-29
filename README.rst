molodemo
========

A demo app for Molo

Getting started
---------------

To get started, clone the repo from git::

    $ git clone https://github.com/praekelt/molodemo.git
    $ cd molodemo
    $ virtualenv ve
    $ pip install molo.core
    $ ./manage.py migrate
    $ ./manage.py createsuperuser
    $ ./manage.py runserver

You can now connect access the demo site on http://localhost:8000
