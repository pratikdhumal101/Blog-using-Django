A simple, open-source blog management platform built with Django, featuring user authentication, search functionality, and more.



Features
User registration & authentication
Custom guest dashboard
Search functionality
Newsletter and email sharing
Disqus integration for comments
REST API with Django Rest Framework
Responsive design (mobile-friendly)
Installation
1. Setup Virtual Environment
sh
Copy code
virtualenv env
source env/bin/activate  # On Mac/Linux
env\Scripts\activate     # On Windows
2. pip install -r requirements.txt
3. Migrate Database & Run Server
sh
Copy code
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
Open http://localhost:8000 to view the app.

Technologies Used
Backend: Django 3.0, Django Rest Framework
Frontend: HTML, CSS, Bootstrap
Others: Disqus, Email Integration
