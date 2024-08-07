# Web Scraper

## Descripción
Este proyecto es un web scraper desarrollado con Django Rest Framework que permite extraer datos de sitios web y almacenarlos en una base de datos.


## Requisitos
- Python 3.x
- Django 3.x o superior
- PostgreSQL (o cualquier otra base de datos soportada por Django)
- Requests (para realizar las solicitudes HTTP)
- BeautifulSoup (para el parsing de HTML)
- Django REST Framework (para la API)

## Instalación
1. Clona el repositorio:
    ```sh
    git clone https://github.com/tu-usuario/web-scraper-django.git
    cd web-scraper-django
    ```

2. Crea y activa un entorno virtual:
    ```sh
    python -m venv env
    source env/bin/activate  # En Windows usa `env\Scripts\activate`
    ```


3. Configura la base de datos en `settings.py`:
    ```python
    DATABASES = {
        'default': {
            'ENGINE': 'django.db.backends.postgresql',
            'NAME': 'XXXX',
            'USER': 'XXX',
            'PASSWORD': 'XXX',
            'HOST': 'localhost',
            'PORT': '5432',
        }
    }
    ```

4. Realiza las migraciones:
    ```sh
    python manage.py makemigrations
    python manage.py migrate
    ```

5. Inicia el servidor de desarrollo:
    ```sh
    python manage.py runserver
    ```
