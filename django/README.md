https://www.youtube.com/watch?v=3vfum74ggHE 
Create and activate a virtual enviroment: 
```bash
python3 -m venv venv
. venv/bin/activate
```

Install Django and Uvicorn
```bash
pip install Django
django-admin startproject todoapp
```

run application:
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

created admin user=nickcarnevale pass=snowleopard
```bash
python manage.py createsuperuser
```