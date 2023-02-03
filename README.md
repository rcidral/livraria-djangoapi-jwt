poetry init (n-n-y)
poetry add django
poetry add djangorestframework
poetry add djangorestframework-simplejwt
poetry shell
django-admin startproject teste .       
django-admin startapp core
python3 manage.py migrate
python3 manage.py runserver
python3 manage.py createsuperuser
python3 manage.py makemigrations