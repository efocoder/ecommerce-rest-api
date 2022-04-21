# ecommerce-api
An Ecommerce API written in Django Rest Framework

## Get Started
- clone the project 
```bash
  git clone git@github.com:efocoder/-ecommerce-api.git
```
- Install Project dependencies
```bash
  pipenv install
```
- Set up database in the settings file (the project uses Postgres, you can change it to suit you)
  
- Run seed to populate the database with dummy data for testing
 ```bash
    pipenv shell
    python manage.py seed_db
```
- Finally start the development server
  ```bash
    python manage.py runserver
  ```