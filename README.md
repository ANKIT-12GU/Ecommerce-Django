# Ecommerce-Django
Django is a powerful Python web framework for building web applications quickly and efficiently. It follows the "batteries-included" philosophy, providing developers with pre-built components for common web development tasks such as URL routing, form handling, authentication, and database management.

## Table of Contents

- [About_Project](#About_Project)
- [TEAM_MEMBERS](#TEAM_MEMBERS)
- [THE_PAGE_SHOP](#THE_PAGE_SHOP)
- [Steps_To_Run](#StepsToRun)
  
## About_Project
Introduction : Introducing my latest project: an E-commerce website crafted with Django, Python, HTML, Bootstrap CSS, and JavaScript. Seamlessly blending frontend flair with Django's backend prowess, it delivers an intuitive and secure shopping experience.

## TEAM_MEMBERS
#### 1.ANKIT KUMAR 
#### 2.ROHIT BORHADE

## THE_PAGE_SHOP  
![image](https://github.com/ANKIT-12GU/Ecommerce-Django/assets/114995661/40138e48-ad22-40b8-aacd-98a81c5d33fc)
# Search The Product Present in Database
eg: iphone 
![image](https://github.com/ANKIT-12GU/Ecommerce-Django/assets/114995661/c369b350-c316-4e84-bd8b-1e9cde24cf0c)
# Fill Details For Order Confirmation
![image](https://github.com/ANKIT-12GU/Ecommerce-Django/assets/114995661/5b35b6a8-cfc4-4617-8369-c29ecc3988ae)
# Contact Us For Any Queries
![image](https://github.com/ANKIT-12GU/Ecommerce-Django/assets/114995661/1fd4a5ff-8771-448c-9422-cf04bbcf72e6)

## StepsToRun
# Steps To Execute This Website On Local Machine , Follow the Steps :
For Git clone : https://github.com/ANKIT-12GU/Ecommerce-Django.git
# step-1 install  virtualenvwrapper 
pip install virtualenvwrapper-win
# step-2 set the virtual environment
mkvirtualenv mpapp
# step-3 install Django
pip install django
# step-4 to make a project 
django-admin startproject myproject
# step-5 change directory to your Project Directory
cd myproject
# step-6 start project
workon mpapp
# step-7 to run the project 
python manage.py startapp myapp
# step-8 to make changes in the database
python manage.py makemigrations 
# step-9  for saving the changes in migrations
python manage.py migrate
# step-10 to create the user access to the database
python manage.py createsuperuser
# step-11  run your Project on Server
python manage.py runserver
# step-12  to include the images in the database
pip install Pillow

