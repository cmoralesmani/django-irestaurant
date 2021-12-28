# iRestaurant

Is a API for restaurant management.

## Development instructions

Create development environment:

```
$ python -m venv env
```

Use development environment:

```
$ source env/bin/activate (Unix)
$ .\env\Scripts\activate (Windows)
```

Install dependencies:

```
$ pip install -r requirements.txt
```

Run migrations:

```
$ python manage.py migrate
```

Create superuser:

```
$ python .\manage.py createsuperuser
Email: admin@irestaurant.com
Password:
Password (again):
Superuser created successfully.
```

Run web api:

```
$ python manage.py runserver
```
