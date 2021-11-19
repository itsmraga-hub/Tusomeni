web: gunicorn --bind 0.0.0.0: learning_log:app
python manage.py collectstatic --noinput
manage.py migrate