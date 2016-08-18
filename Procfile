web: gunicorn config.wsgi:application
worker: celery worker --app=django.taskapp --loglevel=info
