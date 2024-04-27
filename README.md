# Houses Application

I am learning to create Houses App using Python Django, and ReactJS

## Backend - Config

> 1. To be done

```powershell
python -m venv .venv
.\.venv\Scripts\activate

pip install django
pip install djangorestframework
pip install flask

django-admin startproject config
python manage.py runserver

python manage.py migrate

pip install mysqlclient
pip install pika
pip install django-mysql
pip install django-cors-headers

pip freeze > .\requirements.txt
pip install –r requirements.txt

docker build --pull --rm -f "Dockerfile" -t housesservices:latest -t vishipayyallore/housesservices:latest .
```

## Backend - Houses App

```powershell
docker-compose exec backend sh

django-admin startapp houses
```

## Frontend

> 1. To be done

```powershell
npx create-react-app housesweb --template typescript
```
