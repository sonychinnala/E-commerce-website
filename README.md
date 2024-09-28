Django Blog Application
Project Overview
This is a full-featured blog application built using Django. It includes both front-end and back-end components, allowing users to create, view, and manage blog posts. It’s a dynamic platform that demonstrates key concepts in Django such as models, views, templates, and authentication.

Features
User Authentication: Users can register, log in, and log out.
Create, Read, Update, and Delete (CRUD): Authenticated users can create, edit, and delete their own blog posts.
Pagination: Blog posts are displayed with pagination to manage large numbers of entries.
Comment System: Users can comment on posts.
Search Functionality: Allows users to search for posts by title or content.
Responsive Design: A mobile-friendly UI for smooth user experience across devices.
Requirements
Python 3.x
Django 4.x
PostgreSQL or SQLite (default)
Setup Instructions
Clone the repository:

bash
Copy code
git clone https://github.com/sonychinnala/django-blog.git
cd django-blog
Create and activate a virtual environment:

bash
Copy code
python -m venv env
source env/bin/activate  
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set up the database:

bash
Copy code
python manage.py migrate
Create a superuser for admin access:

bash
Copy code
python manage.py createsuperuser
Run the development server:

bash
Copy code
python manage.py runserver
Access the application in your browser at:

arduino
Copy code
http://127.0.0.1:8000











