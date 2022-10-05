# DjangoDockerComposeDeploy




docker-compose build

docker-compose run --rm app sh -c "django-admin startproject app ."

docker-compose build

docker-compose run --rm app sh -c "python manage.py startapp core"

docker-compose run --rm app sh -c "python manage.py makemigrations"

docker-compose up