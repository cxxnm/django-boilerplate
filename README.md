# Django Project Boilerplate
## Description:
Ready to dev bolierplate with `python3.11` and `django-v4.2.4`
### Builtin packages (no need to install) 
```
celery
djangorestframework
django-filter
django-jazzmin
django-debug-toolbar
```

### Preinstallations
Python packaging and dependency management \
```
poetry
```

To Run project:
```
docker
docker-compose
```

### Setup project
Create `.env` file
```
cp .env-example .env
```
Modify `.env` file
```
ENV=DEV
VIRTUAL_HOST=...
DJANGO_SECRET_KEY=...

POSTGRES_HOST=...
```
### How to run

Run command to start your project: \

```
docker compose up -d
```
