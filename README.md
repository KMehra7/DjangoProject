# DjangoProject
Django Login System

1. This Django project aims to create a robust system with features for user signup, login, and profile management.

2. It includes functionalities such as user registration, user data retrieval, updating user details, and deleting user accounts.

3. The project utilises Django's built-in features for model creation, views implementation, URL routing, and template rendering to achieve seamless user interaction and data management.

4. Additionally, thorough testing with Postman ensures the reliability and functionality of the CRUD operations.


## Task 1
Set up a Django project named "Login System" with a virtual
environment and a Django application named "Loginify".
Microtasks:

1. Create a Virtual Environment: DjangoAssignment
- Create a virtual environment named "DjangoAssignment" to
isolate project dependencies.

2. Activate the Virtual Environment
- Activate the virtual environment to use it for installing and
running Django.

3. Install Django
- Install Django within the activated virtual environment to use it
for the project.

4. Create a New Django Project: Login System
- Create a new Django project named "Login System" where all
configurations and settings will reside.

5. Create a New Django Application: “Loginify”
- Create a new Django application within the project to handle
the login functionality.

## Task 2

CREATE VIEWS AND URLS FOR LOGIN SYSTEM

Create views and define URL patterns for the "Login System"
Django application to handle login functionality.
Microtasks:

1.Create Views

Create views within the "Loginify" Django application to handle
login functionality.
Create a view that returns an HTTP response with the text
"Hello, world!" for testing purposes.

2. Define URL Patterns

Define URL patterns in the "urls.py" file of the "Loginify" Django
application to map views to specific URLs.
Ensure that the URL patterns are properly configured to match
the desired endpoints.

## Task 3

Define Models for Login System

Define models, implement views, and set up URLs and templates in
Loginify.
Microtasks:

1.Models :

Create a “UserDetails” Model which has fields below
Username: Use models.CharField(max_length=50,
primary_key=True)
Email: Use models.EmailField(unique=True)
Password: Use models.CharField(max_length=12,
blank=True)

Implement views in views.py for signup, login.

2. Define URLs and Templates
Define URL patterns in urls.py for the implemented views.
Create HTML templates for signup and login forms,
confirmation page, and success message.
Upon successful signup, redirect to the login page.
Upon successful login, display a success message.

3.Signup view:
Implement the Signup view in views.py, which handles user
registration with inputs for name, email, and password.
Ensure that the email field is unique.

4. Login view:
Implement the Login view in views.py, which requires inputs
for email and password.

## Task 4
MODELS & ADMIN

Set up a superuser account using Django's manage.py command
and verify the superuser endpoint by accessing the admin
interface to ensure proper configuration and functionality.

1. Setup Superuser
- Create a superuser using Django's manage.py command.
python manage.py createsuperuser
- Verify the superuser endpoint by visiting the admin interface.
