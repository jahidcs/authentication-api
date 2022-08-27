# Django Rest Framework Authentication Project

### Functionality

1. Custom user creation
2. User registration
3. User signin/login
4. change password
5. reset password link sending by email
6. reset password
7. user profile/info view

### Packages used

    django
    djangorestframework
    djangorestframework_simplejwt
    django-cors-headers
    django-dotenv

### Project run steps[Linux]

    1. Initialize venv: python3 -m virtualenv venv
        Activate venv: source/venv/bin/activate
    2. Install packages: pip install -r requirements.txt
    3. Create migration file: python3 manage.py makemigrations
    4. Apply migration: python3 manage.py migrate
    5. Create superuser for access admin panel: python3 manage.py createsuperuser
        - provide email, name, password
    6. Run in localhost: python3 manage.py runserver

#### Note: To test the apis in postman, import api collection [Tele Health.postman_collection.json] file in postman
