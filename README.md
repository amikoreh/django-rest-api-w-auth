# django-rest-api-w-authentication
#### A Django (Python) REST API using [Django REST framework](http://www.django-rest-framework.org/)

##build commands:
##### Create a new virtual environment using virtualenv
- virtualenv -p /usr/local/bin/python3 venv
- source venv/bin/activate
--- `deactivate` when done using virtual environment, you will need to re-activate environment each time if not in (venv)
##### Install package requirements
- pip install Django
- pip install djangorestframework
##### Freeze environment packages
- touch requirements.txt
- pip freeze > requirements.txt
--- Run package updates: pip install -r requirements.txt --upgrade
##### Create a new project to work with
- django-admin startproject rest_api
##### Create new app using startapp
- python3 manage.py startapp api
##### Run test cases
- python3 manage.py test
##### Run migrations to create database
- python3 manage.py makemigrations
- python3 manage.py migrate
##### Start up Django's development server
- python3 manage.py runserver
- Visit [http://localhost:8000/bucketlists/](http://localhost:8000/bucketlists/) after runserver.

##### Add new admin user for authentication:
- python manage.py createsuperuser

##### Useful links:
http://docs.python-guide.org/en/latest/
https://code.djangoproject.com/
https://scotch.io/tutorials/
https://scotch.io/tutorials/build-a-rest-api-with-django-a-test-driven-approach-part-1
https://wiki.python.org/moin/
http://www.django-rest-framework.org/
https://github.com/andela-uawili/django-bucketlist-application