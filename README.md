# Blogging Web Application
## About
This Project is made using Python 3.6 + Django and Database is SQLite. This web application creates an very basic blog using Django.It allows blog authors to create blogs using the Admin site with login and registration functionality.
## Screenshots
![Screenshot (732)](https://user-images.githubusercontent.com/73628133/168130317-2a8ae363-fe88-4f44-9b32-914455b3114d.png)

![Screenshot (732)](https://user-images.githubusercontent.com/73628133/168129762-f6740382-aaa2-449a-9a0b-840f0794e149.png)

![Screenshot (731)](https://user-images.githubusercontent.com/73628133/168129548-a91c57f1-d430-4ce0-943e-88fbf7c58c0f.png)

## Quick Start
Clone This Project
https://github.com/chazuttu/blogs.git

Install Dependencies
* pip install -r requirements.txt


Set Database (Make Sure you are in directory same as manage.py)

* python manage.py makemigrations
* python manage.py migrate


Create SuperUser
* python manage.py createsuperuser

Run Server
* python manage.py runserver

*Open a browser to http://127.0.0.1:8000/admin/ to open the admin site*

*Open tab to http://127.0.0.1:8000/home/ to see the main site.*


