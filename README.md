# Recepie-API
REst
Django Helper functions used in our apps

BaseUserManager -> normalize_email
                -> set_password
                -> self._db


1: docker-compose run --rm app sh -c " django-admin.py startproject app

Testing:
docker-compose run app sh -c "python manage.py test && flake8"

docker compose build for install flake8 from requirements

https://travis-ci.com/github/pranavchandran/Recepie-API/branches


Create an APP
###docker-compose run app -sh -c "python manage.py startapp core"

Run Only unit test
docker-compose run app sh -c "python manage.py test"

Makemigrations
docker-compose run app sh -c "python manage.py makemigrations core"

For run the server
docker compose up 

Create superuser
docker-compose run app sh -c"python manage.py createsuperuser"
