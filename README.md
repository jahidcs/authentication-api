# Django Rest Framework Authentication Project

### Packages used

1. django
2. djangorestframework
3. djangorestframework_simplejwt
4. django-cors-headers
5. django-dotenv

### Project run steps

1. Initialize venv: python3 -m virtualenv venv
2. Install packages: pip install -r requirements.txt
3. Create migration file: python3 manage.py makemigrations
4. Apply migration: python3 manage.py migrate
5. Create superuser for access admin panel: python3 manage.py createsuperuser
   - provide email, name, password
6. Run in localhost: python3 manage.py runserver
