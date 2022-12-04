# CINEMA SERVICE

The project is django REST's API for managing cinema service.

## Instalation

### You will need Python and PostgreSQL before starting it.

```
git clone https://github.com/Yurnerroo/cinema_serivice_api
cd cinema_service_api
python3 -m venv venv
venv/Scripts/activate
pip install -r requirements.txt
export/set DEBUG=True
export/set DB_HOST=<host name>
export/set DB_NAME=<db name>
export/set DB_USER=<user name>
export/set DB_PASSWORD=<db password>
python manage.py migrate
python manage.py runserver
```

## For Debugger:

```export/set DEBUG=True```

## For Docker:

```
docker-compose build
docker-compose up
```

## Features

- Swagger documentation
- Docker usage
- JWT authentication
