### PickPics
##### A backend focused Social Website for bookmarking images from other platforms.

## About The Project
This is a backend focused Social website where users can bookmark images from other websites using a bookmarklet.  User can follow other users and  can give a like to their bookmarked images. 

### Features
* Redis sorted sets based ranking system for most viewed images
* Redis based system to store views.
* Social authentication (Facebook, Twitter, Google)
* Ajax based Like system, View system and Follow system
* Infinite Scrolling 
* Activity stream to display notifications and updates
* Optimized querysets for fast data fetching 

## Getting Started

### Prerequisites
You should have Python 3x and Redis installed on your machine.

### Built with
* Django
* Python
* AJAX
* Jquery
* Redis

### Installation
Just make a virtual environment in the project directory and activate it.
Then install all the dependencies given in requirements.txt using
#### `pip install -r requirements.txt` 

Then make the migrations.
####  `python manage.py makemigrations`

Let's sync your database with the models.
#### `python manage.py migrate`

Then start the development server.
#### `python manage.py runserver`

If you have to login using Social authentication, You can use SSL  certificate credentials
#### `python manage.py runserver_plus --cert-file cert.crt`
<br/>

## License
Distributed under the MIT License. See `LICENSE` for more information.

## Contact
Shivam Maithil - shivammaithil1008@gmail.com

Project Link - https://github.com/Shivam-Maithil/PickPics
