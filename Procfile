release: python manage.py createsuperuser
release: python manage.py migrate
web: gunicorn knowledgeArchive.wsgi --log-file -