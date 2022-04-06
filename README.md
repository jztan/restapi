# restapi

## Prerequisite and Installation
- Install Python 3.7
- Install requirement packages via pip
```
pip install -r requirements.txt
```

## Development
- Django Migration
```
puyhon manage.py migrate
```

## Testing
```
puyhon manage.py runserver
```

## Generate OpenAPI Schema
```
python ./manage.py generateschema --file openapi-schema.yml
```