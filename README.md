# django-images
$ chmod 777 app/
$ docker-compose run --rm app django-admin startproject app .
$ chmod -R 777 app/app
$ docker-compose run --rm app python manage.py migrate
