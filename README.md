# First Django Project!

### Following tutorial from:
https://docs.djangoproject.com/en/5.0/howto/windows/
https://docs.djangoproject.com/en/5.0/intro/tutorial01/

Using Readme from: https://www.toptal.com/developers/gitignore/api/windows,linux,macos,visualstudiocode,python,virtualenv,django,dotenv

### Setup Info:

* `pip install mysqlclient` will install mysqlclient
* fill in the User and Password on 81 and 82 of settings.py
* Create the database schema manually.
* Run `python manage.py migrate` to set up tables.


### Some commands:
* `python manage.py runserver` will run a development server at [http://127.0.0.1:8000/](http://127.0.0.1:8000/)

### How to change models:
- Change your models (in models.py).
- Run `python manage.py makemigrations` to create migrations for those changes
- Run `python manage.py migrate` to apply those changes to the database.