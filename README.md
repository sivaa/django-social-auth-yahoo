django-social-auth-yahoo
===========================

Yahoo openID integration for Django Admin Interface using django-social-auth 

Installation
------------

- $ virtualenv django-social-auth-yahoo
- activate the virtual environment (Source/activate.bat (or)  source bin/activate) 
- $ pip install -r requirements.txt (uncomment the MySQL-python if you are using mysql)

- Create a yahoo project in https://developer.apps.yahoo.com/projects/ and update YAHOO_CONSUMER_KEY & YAHOO_CONSUMER_SECRET settings


Configuration
------------

The new users can be given the super user permissions using

SOCIAL_AUTH_CREATE_USERS_AS_SUPER_ADMIN = True