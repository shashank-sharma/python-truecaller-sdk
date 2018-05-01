# Using Truecaller SDK with Django and Heroku

![Heroku](https://heroku-badge.herokuapp.com/?app=django-login&root=admin&style=flat)

Truecaller-SDK helps you to authenticate user phone number without any OTP verification. It will simply ask for phone number and on submit it will send one push notification which on click authenticates the user for that particular web app. This repository used Django framework and TrueSDK to implement this feature.

Live version: [Site](http://django-login.herokuapp.com/)

Note: If you are concerned about privacy then don't enter your mobile number in django-login web app because it stores the name and phone number if any users authenticate over there.

### Blog
In case you are wondering how to do this, then feel free to visit my blog on this: ![Link](https://mythicalpython.wordpress.com/2018/05/01/using-truecaller-sdk-with-django-and-heroku/)

### Workflow

<img src="https://mythicalpython.files.wordpress.com/2018/05/truecaller.png?w=1100">

### Getting Request ID:

<img src="https://mythicalpython.files.wordpress.com/2018/04/screenshot-from-2018-04-30-23-05-29.png?w=1100">

### Fetching User data from access Token:

<img src="https://mythicalpython.files.wordpress.com/2018/05/screenshot-from-2018-05-01-12-08-33.png?w=1100">

### Why I implemented ?

Currently the documentation of original repository was not that helpful and I found that there are so many people who are stuck, so I created this blog/repository to help out everyone.

Original repository: https://github.com/truecaller/web-login
