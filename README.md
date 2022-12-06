# Django Ecommerce Web App

It is a django web app as well as api for ecommerce web app. I is made with django rest frameword and django web framework.

## How to install it?



```bash
    cd django-ecommerce
```

- Create a Virtualenv and the project directory

```bash
    virtualenv env
```

- Activate the virtualenv

```bash
    source env/bin/activate
```

- Install the project Dependencies

```bash
    pip install -r requirements.txt
```

- Make The Migrations To the database

```bash
    python manage.py migrate
```

- Create a superuser

```bash
    python manage.py createsuperuser
```

- Change the razorpay credentials in the settings file

- Spin Up The Django Developement Server

```bash
    python manage.py runserver
```

Now You Are all set and the server Is Running on the url http://localhost:8000 and can create the products from django admin.
