# Flask Postgres Boilerplate

This is a boilerplate for a Flask app that can run as a virtualenv, Heroku or Docker application.

If you install Postgres locally using Homebrew, You can start and stop Postgres by doing `pg_ctl -D /usr/local/var/postgres start` and stopping with `pg_ctl -D /usr/local/var/postgres stop`.

Remember to run `python manage.py db init` to create tables and `python manage.py db migrate` and/or `python manage.py db upgrade` when you modify them.
