# Django CRUD with Authentication

This is a full-stack web application built with Django, focused primarily on understanding back-end development. 
It implements a task manager with full CRUD functionality and user authentication.
 
**Deploy:** [django-auth-crud-hp0v.onrender.com](https://django-auth-crud-hp0v.onrender.com)


## Functions

- Full CRUD functionality for tasks (create, read, update, delete)
- User authentication (registration, login, logout)
- Route protection based on session status
- Task filtering by status (pending / completed)
- Styled interface with Bootstrap 5
- Production deployment with Render + WhiteNoise + Gunicorn

## Tech Stack


![Python](https://img.shields.io/badge/Python_3.14-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django_6.0.6-092E20?style=flat&logo=django&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap_5-7952B3?style=flat&logo=bootstrap&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat&logo=sqlite&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-499848?style=flat&logo=gunicorn&logoColor=white)
![WhiteNoise](https://img.shields.io/badge/WhiteNoise-000000?style=flat)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat&logo=render&logoColor=white)

## Project structure

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

## Local installation

```bash
git clone https://github.com/joseRPM/Developer
cd Developer/django
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```


## Conclusions
This is a full-stack web application built with Django, with a primary focus on understanding back-end development. It implements a task manager with full CRUD functionality and user authentication.

The project is designed to demonstrate the complete back-end development lifecycle: data modeling, views, forms, authentication, and deployment, while also covering the fundamentals of frontend development.
