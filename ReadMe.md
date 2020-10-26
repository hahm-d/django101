## Django 
https://www.django-rest-framework.org/

# set-up
https://medium.com/swlh/build-your-first-rest-api-with-django-rest-framework-e394e39a482c

# create directory and start virtual environment (additionally activate)
virutalenv -p pthon3 .
source bin/activate 
# to exit virutalenv
type deactivate

# create project
django-admin startproject django101

# start server
python3 manage.py runserver

# create the api app
python3 manage.py startapp api

# update installed_apps in settings.py
'api.apps.ApiConfig'

# migrate initial models
python3 manage.py migrate

# create super user
python3 manage.py createsuperuser

# create api models / migrate
python3 manage.py makemigrations
python3 manage.py migrate

# register models in admin 
import and add route

## Set up Django REST Framework
pip install djangorestframework

# add framework to site settings
'rest_framework'

# add serializer to Hero model (api)
create serializers.py

# setup Views - query database, pass database queryset into serializer
views.py

# adding site URLs
django101/urls.py

# add api URLs
create urls.py in api

# adding IDs for each Hero (serializer)
update api/serializers.py 



## Other

# adding gitignore generated
https://www.toptal.com/developers/gitignore
