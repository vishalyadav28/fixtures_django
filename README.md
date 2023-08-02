# fixtures_django
In this we will see how to load data in DB using fixtures

## project setup

run cmd

```
django-admin startproject myproject
cd myproject
python manage.py startapp books

```

create model

```
python manage.py makemigrations
python manage.py migrate
```

load data using

```python

python manage.py loaddata books/fixtures/initial_books.json
-----------------------------------------------------------
python manage.py loaddata app_name/folder/file_name.json


```
