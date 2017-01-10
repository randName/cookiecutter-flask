cookiecutter-flask
==================

A Flask template for cookiecutter_.

.. _cookiecutter: https://github.com/audreyr/cookiecutter

Main differences
----------------

- Lightweight, e.g. for simple CRUD sites that do not need logins
- No User model and authentication extensions (seriously, use Django for those)
- No form extensions (mainly using AJAX forms. WARNING: no csrf)
- No asset management and cache
- No debug toolbar

Use it now
----------

Just Kidding. No, don't actually use it yet.

::

    $ pip install cookiecutter
    $ cookiecutter https://github.com/randName/cookiecutter-flask.git

You will be asked about your basic info (name, project name, app name, etc.). This info will be used in your new project.

Features
--------

- Bootstrap 3 and Font Awesome 4 with starter templates
- Flask-SQLAlchemy
- Easy database migrations with Flask-Migrate
- Procfile for deploying to a PaaS (e.g. Heroku)
- pytest and Factory-Boy for testing (example tests included)
- Flask's Click CLI configured with simple commands
- Optional bower support for frontend package management
- Utilizes best practices: `Blueprints <http://flask.pocoo.org/docs/blueprints/>`_ and `Application Factory <http://flask.pocoo.org/docs/patterns/appfactories/>`_ patterns

Inspiration
-----------

- `Original cookiecutter-flask <https://github.com/sloria/cookiecutter-flask>`_
- `Building Websites in Python with Flask <http://maximebf.com/blog/2012/10/building-websites-in-python-with-flask/>`_
- `Getting Bigger with Flask <http://maximebf.com/blog/2012/11/getting-bigger-with-flask/>`_
- `Structuring Flask Apps <http://charlesleifer.com/blog/structuring-flask-apps-a-how-to-for-those-coming-from-django/>`_
- `Flask-Foundation <https://github.com/JackStouffer/Flask-Foundation>`_ by `@JackStouffer <https://github.com/JackStouffer>`_
- `flask-bones <https://github.com/cburmeister/flask-bones>`_ by `@cburmeister <https://github.com/cburmeister>`_
- `Flask Official Documentation <http://flask.pocoo.org/docs/>`_


License
-------

BSD licensed.
