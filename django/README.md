# P-04 — Django CRUD con Autenticación

**Stack:** Python · Django · Bootstrap · SQLite  
**Área:** Back-end  
**Deploy:** [django-auth-crud-hp0v.onrender.com](https://django-auth-crud-hp0v.onrender.com)

---

## Descripción

Aplicación web construida con Django que implementa un gestor de tareas
con CRUD completo y sistema de autenticación de usuarios.
Proyecto orientado a demostrar el ciclo completo de desarrollo back-end:
modelado de datos, vistas, formularios, autenticación y despliegue en producción.

---

## Funcionalidades

- CRUD completo de tareas (crear, leer, actualizar, eliminar)
- Autenticación de usuarios (registro, login, logout)
- Protección de rutas según estado de sesión
- Filtro de tareas por estado (pendientes / completadas)
- Interfaz estilizada con Bootstrap 5
- Deploy en producción con Render + WhiteNoise + Gunicorn

---

## Stack técnico

| Herramienta  | Uso                    |
|--------------|------------------------|
| Python 3.14  | Lenguaje base          |
| Django 6.0.6 | Framework web          |
| Bootstrap 5  | Estilos e interfaz     |
| SQLite       | Base de datos          |
| Gunicorn     | Servidor WSGI          |
| WhiteNoise   | Archivos estáticos     |
| Render       | Plataforma de deploy   |

---

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
