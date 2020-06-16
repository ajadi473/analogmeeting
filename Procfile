web: gunicorn manage:app
web: python manage.py runserver 0.0.0.0:$PORT
release: python manage.py db upgrade