# API MOVIES DRF

API for registering actors, reviews, movies, and existing genres. JWT authentication, serializers, command created to import CSV of actors into the database following PEP8."

## Requirements

Certifique-se de que você tenha os seguintes requisitos instalados em seu sistema:

- Python (versão recomendada: 3.7 ou superior)
- Django (instalado automaticamente ao seguir as instruções abaixo)
- Outras dependências listadas no arquivo `requirements.txt`

Make sure you have the following requirements installed on your system:

- Python (recommended version: 3.7 or higher)
- Django (automatically installed by following the instructions below)
- Other dependencies listed in the `requirements.txt` file


## Dependencies Installation

With the virtual environment activated, install the project dependencies using the command:
```bash
pip install -r requirements.txt
```


## Execute the migrate

After installing the dependencies, apply the migrations to the database with the command:
```bash
python manage.py migrate
```


## Create the superuser

After installing the dependencies, apply the migrations to the database with the command:
```bash
python manage.py createsuperuser
```

## Run the server

Now the project can be initialized with the command:
```bash
python manage.py runserver
```

After this, the system will be ready to be accessed at (remember to use superuser username and password):
[http://localhost:8000/api/v1/authentication/token/](http://localhost:8000/api/v1/authentication/token/)

"Note: It is highly recommended to use Postman to fetch the access token."