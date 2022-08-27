# Django Rest Framework Authentication Project

### Functionality

    Custom user creation
    User registration
    User signin/login
    change password
    reset password link sending by email
    reset password
    user profile/info view

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

#### Note: To test the apis in postman, import api collection [Tele Health.postman_collection.json] file in postman
