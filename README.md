# Django CRUD con Autenticación

This is a full-stack web application built with Django, focused primarily on understanding back-end development. 
It implements a task manager with full CRUD functionality and user authentication.
 
**Deploy:** [django-auth-crud-hp0v.onrender.com](https://django-auth-crud-hp0v.onrender.com)


## Funcionalidades

- CRUD completo de tareas (crear, leer, actualizar, eliminar)
- Autenticación de usuarios (registro, login, logout)
- Protección de rutas según estado de sesión
- Filtro de tareas por estado (pendientes / completadas)
- Interfaz estilizada con Bootstrap 5
- Deploy en producción con Render + WhiteNoise + Gunicorn

## Tech Stack

![Python](https://img.shields.io/badge/Python_3.14-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django_6.0.6-092E20?style=for-the-badge&logo=django&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=for-the-badge&logo=gunicorn&logoColor=white)
![WhiteNoise](https://img.shields.io/badge/WhiteNoise-000000?style=for-the-badge)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)

## Estructura del proyecto

```
django/
├── djangocrud/
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
├── tasks/
│   ├── models.py
│   ├── views.py
│   ├── forms.py
│   └── templates/
├── build.sh
├── manage.py
└── requirements.txt
```

---

## Instalación local

```bash
git clone https://github.com/joseRPM/Developer
cd Developer/django
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

---

## Estado

 Deployado en producción
