# Packages

django
python-dotenv
djangorestframework
pytest
pytest-django

# Commands

django-admin startproject drfecommerce
./manage.py runserver

from django.core.management.utils import get_random_secret_key
print(get_random_secret_key())