# docker_django_postgres

# terminal
```
docker-compose run web django-admin.py startproject composeexample .
docker-compose up -d
```

# settings.py
```
ALLOWED_HOSTS = ['*']

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.postgresql',
        'NAME': 'postgres',
        'USER': 'postgres',
        'HOST': 'db',
        'PORT': 5432,
    }
}
```

# web access

```
localhost:8000
```