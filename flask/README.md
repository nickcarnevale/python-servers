Flask
https://flask.palletsprojects.com/en/stable/quickstart/ 
https://flask-sqlalchemy.readthedocs.io/en/stable/quickstart/ 

Create and activate a virtual enviroment: 
```bash
python3 -m venv venv
. venv/bin/activate
```

Install Flask and Flask-SQLAlchemy
```bash
pip install Flask
pip install Flask-SQLAlchemy
```

Export env variables and Run
```bash
export FLASK_APP=app.py
export FLASK_ENV=development
flask run
```


Run with Dockerfile and docker-compose.yml
```bash
docker compose up --build
```