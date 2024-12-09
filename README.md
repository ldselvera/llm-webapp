## Creating a simple fast api application using llm 
### Create conda environment and activate
### Install packages
``` 
pip install -r requirements.txt
pip install "fastapi[all]"
```

### Run application locally
```
python main.py
uvicorn main:app --reload
```
### URL
http://127.0.0.1:8000 or http://0.0.0.0:80/response

### Testing
Use test_fastapi.ipynb

### Docker
```
docker build -t llm-app .
docker run -d -p 8080:80 llm-app
```
### Testing
Use test_fastapi.ipynb