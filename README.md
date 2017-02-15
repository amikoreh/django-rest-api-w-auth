# django-rest-api-w-authentication
###### A Django (Python) REST API using [Django REST framework](http://www.django-rest-framework.org/)

##commands:
virtualenv -p /usr/local/bin/python3 venv
source venv/bin/activate
pip install Django
touch requirements.txt
pip freeze > requirements.txt
django-admin startproject rest_api
pip install djangorestframework
python3 manage.py startapp api
python3 manage.py test
python3 manage.py makemigrations
python3 manage.py migrate
python3 manage.py runserver

####Visit http://localhost:8000/bucketlists/ after runserver.

python manage.py createsuperuser  -- create new admin user
