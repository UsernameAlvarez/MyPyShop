# MyPyShop

This App belongs to an excercise of the course: 
[**Python Tutorial for Beginners - Learn Python for Web Development**](https://www.youtube.com/watch?v=_uQrJ0TkZlc&t=21833s)
of the series **Programming with Mosh**, available in Youtube. Where he Built a Website with Django Framework.

## Before you begin

Install the dependencies by running the following command in the terminal.

```
pip install requirements.txt
```
>Make sure you are using python 3 or above.

## Getting started

`manage.py` is a command line utility that allows you to interact with this Django project in different ways.

### Usage

For purpose to create new migrations based on the changes you have made to your models run the following command.
```
python manage.py makemigrations
```

For the purpose to applying and unapplying migrations run the following command.
```
python manage.py migrate
```

For the purpose to start the server run the followin command, the go to the route 
http://127.0.0.1:8000/ to see the available products
```
python manage.py runserver
```

For the purpose to manage the products (add/edit/delete), you should go the administrative panel in the route http://127.0.0.1:8000/admin 
but first run the following command to create a user.
```
python manage.py createsuperuser
```

## Built With 🛠️

* [Python 3.7] -  Programming Language.
* [Django 2.1.5] -  Framework.

## Versioning. 📌

For the versions available, see the [tags on this repository](https://github.com/UsernameAlvarez/MyPyShop/tags).

## Authors ✒️

* **Genesis Alvarez** - *Initial work* - [stashconsulting](https://github.com/stashconsulting)

* **Shailyn Ortiz** - *Maintainer* - [stashconsulting](https://github.com/stashconsulting)

## Acknowledgments
This project was born when I wanted to improve my python skills and learn about django framework. In the past, I had only used flask framework.

---
⌨️ with ❤️ by [Alvarez](https://github.com/UsernameAlvarez)
