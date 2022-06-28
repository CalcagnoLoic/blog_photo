web: gunicorn django_project.wsgi:blog-photo-django --log-file - --log-level debug
python manage.py collectstatic --noinput
manage.py migrate