web: gunicorn wsgi:app
web: python manage.py 0.0.0.0:$PORT
release: python manage.py db upgrade
