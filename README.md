# django-auth-crud

Saludos y bienvenidos. El repositorio que estas consultando actualmente es un proyecto desarrollado en Django 4.2.2, que tiene como objetivo,
autenticar a nuestros usuarios (Login,Register, Rutas protegidas, y mas), CRUD completo que permite cambiar operar con una base de datos, y poder usar el panel de administración,

# Requisitos previos
### Asegúrate de tener los siguientes requisitos previos instalados en tu sistema:
    Python (3.11.4)
    Git Bash

# Instalación

Sigue los pasos a continuación para clonar el repositorio:

    $ git clone https://github.com/02Alexis/django-auth-crud.git

# Configuración del entorno virtual

Sigue los pasos a continuación para configurar y activar un entorno virtual:

    $ cd django-auth-crud
    $ py -m venv venv
    $ venv\Scripts\activate

# Instalación de dependencias
Asegúrate de tener el entorno virtual activo y ejecuta el siguiente comando para instalar las dependencias del proyecto:

    pip install -r requirements.txt

# Migraciones de la base de datos

Ejecuta los siguientes comandos para aplicar las migraciones y crear las tablas en la base de datos:

    python manage.py makemigrations
    python manage.py migrate

# Iniciar el servidor local

Ejecuta el siguiente comando para iniciar el servidor local:

    $ python manage.py runserver

# Recursos adicionales

· [Django Documentation.](https://www.djangoproject.com/download/)
  
