release: python manage.py migrate
web: gunicorn django_snippets.wsgi
worker: celery -A django_snippets worker -l info