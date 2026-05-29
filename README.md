# Read Me
## Installation

```powershell
pip install -r requirements.txt
```

## Running

```powershell
python app.py
```

## Testing

```powershell
pytest
```

## Docker

```powershell
docker build -t flask-app .
docker run -p 5000:5000 flask-app
docker exec -it flask-app pytest
```

