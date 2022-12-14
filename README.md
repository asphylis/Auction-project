# Auctions
Auctions is a mock e-commerce auctioning website where users can register to bid on other users' listings, leave comments on listings, add listings to their watchlist, and create their own listings. This project was made as part of the online class CS50's Web Programming with Python and JavaScript by HarvardX.

## Setup
Since this project is made with Django, having python and necessary python packages to run Django downloaded are necessary. In order to run the site, first clone the respository. Next, on a terminal window, change your directory into the repository and run the following lines of code to setup the database:

```
python3 manage.py makemigrations auctions
python3 manage.py migrate
```
Note that the previous lines of code are only required the first time the project is being run. After that, the database does not need to be setup again.

Last, to boot the server, you must run the following line of code:

``` python3 manage.py runserver```

Once the server is booted, you will be provided with a URL to access the site. To shut down the server, use the keyboard shortcut cntrl + c while on the terminal.

## Accessing the Admin page
To get a look at the structure of the models in the database, you can login to the admin page. In order to do this, add "/admin" after the URL (ex. http://127.0.0.1:8000/admin).
But before that run the command
```
python manage.py createsuperuser
```
You will be asked for the following:
username, email, password
enter values accordingly and you should be good to go.
