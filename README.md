# Django-user-details

This is a simple Django application with User and ActivityPeriod models, to populate the database with some dummy data, and design an API to serve that data in the json format given above.

The hosted application: http://ulure.pythonanywhere.com/users/

There are two models:

1. User Model

2. ActivityPeriod Model

They are related as many to many field

To run this project install the dependenies from the **requirements.txt** file.

and then **python3 manage.py runserver** to start the server.

Then go to **localhost:8000/users** to see the dummy data.

To add data we need to add it from the admin panel.
