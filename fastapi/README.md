Create and activate a virtual enviroment: 
```bash
python3 -m venv venv
. venv/bin/activate
```

Install FastAPI and Uvicorn
```bash
pip install fastapi
pip install uvicorn
pip install python-multipart sqlalchemy jinja2
```

Run the server
```bash
uvicorn app:app --reload
```