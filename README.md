# DRF Cinema API

API service for cinema management written on Django REST Framework (DRF). Using this API, developers can interact with the cinema management system programmatically, for example to retrieve information about movie showtimes, make bookings, or manage customer data.

## Installing using GitHub:
Install PostgreSQL and create db.
```
git clone https://github.com/me1nyk/DRF-Cinema-API.git
cd DRF-Cinema-API
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
mv .env.sample .env
```
Place expected values of all variables into .env file.
```
source .env
sh start.sh
```

## Run with Docker:
```
docker-compose build
docker-compose up
```

## Getting access:
- create user via /api/user/register/
- get a JWT token via /api/user/token/

## Features:
- JWT authenticated
- Admin panel /admin/
- SWAGER documentation /api/doc/swagger/
- Managing orders and tickets
- Creating movies with genres, actors
- Creating cinema halls
- Adding movie sessions
- Filtering movies and movie sessions
