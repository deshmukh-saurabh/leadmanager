# Lead Manager API built using Django REST Framework

## 1. Install dependencies
```sh
pip install -r requirements.txt
```

## 2. Create a .env file
- Add your django app Secret key, Database name, user and password to it as shown below
```sh
SECRET_KEY=<your_secret_key_without_quotes>
DB_NAME=<your_db_name_without quotes>
DB_USER=<your_db_user_without_quotes>
DB_PASSWORD=<your_db_password_without_password>
```

## 3. Database used is PostgreSQL, make sure you add your own credentials in the .env file

## 4. Serve API on localhost:8000
```sh
python leadmanager/manage.py runserver
```

## 5. Use postman to test it.

Extensive documentation with examples [here](https://documenter.getpostman.com/view/10646104/TVCgynHv).