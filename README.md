# Blog App

This is my first Django web app.

The application enables users to create accounts, from which they can publish, update and delete blog posts. The app has log in/log out functionality, and users can reset their passwords if required.

Profiles are automatically created for users, and they will be assigned a default profile picture which can be updated. Some routes in the app are viewable only by logged in users. 

This app uses various features available in Django, including its user authentication, content administration and object relational mapper (ORM) features. 

The app is hosted on Herkou, and can be visited here: https://harrietblogapp.herokuapp.com/

## Technologies
* Python
* Django
* SQLite3
* HTML
* Bootstrap
* Crispy Forms
* Pillow
* Heroku


## Installation

Clone the repository.

```$ git clone https://github.com/hpellis/blog_app```

Navigate to the directory. 

```$ cd blog_app```

Install Django

```$ pip install django```

Run the app file.

```$ python manage.py  runserver```

Navigate to the local host address in your browser to see the app running. 

In order for the password reset feature to work, export environment variables EMAIL_USER and EMAIL_PASS (gmail address and app password) in .bash_profile.

<img src="/final_images/final_version.png"
     alt="Image of application home page"
     style="float: left; margin-right: 10px;" />

