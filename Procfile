web: gunicorn weatherproject.wsgi --log-file - 
#or works good with external database
web: python manage.py migrate && gunicorn weatherproject.wsgi
