Everything about using Celery with Django.

Strat django project command
python manage.py runserver 127.0.0.1:8000

Start elery beat command
celery -A django_celery_project beat -l INFO

Strat celery worker process command
celery -A django_celery_project.celery worker --pool=solo -l info