## Getting Started

## Creating a new project

`sudo docker-compose run web django-admin startproject <my_new_django_project> .`

## Config the DB

```py
# settings.py
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'postgres',
        'USER': 'postgres_user',
        'PASSWORD': 'postgres_pass',
        'HOST': 'db',
        'PORT': 5432,
    }
}
```

## Starting and stopping the app

Start with `docker-compose up` and stop with `docker-compose down`
