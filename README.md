# django-tutorial
django tutorial

### get start project

make a new django project.
```
django-admin startproject <project name>
```

start django application (port 8080)
```
cd <project name>
python manage.py runserver 8080
```

### directory structure

app // root directory name<br>
┣ db.splite3<br>
┣ manage.py // command line utility for django [ref](https://docs.djangoproject.com/ja/2.0/ref/django-admin/)<br>
┗ app # package directory<br>
&nbsp;&nbsp;&nbsp;&nbsp;┣ __init__.py // [ref](https://docs.python.org/3/tutorial/modules.html#tut-packages)<br>
&nbsp;&nbsp;&nbsp;&nbsp;┣ settings.py // setting for application [ref](https://docs.djangoproject.com/ja/2.0/topics/settings/)<br>
&nbsp;&nbsp;&nbsp;&nbsp;┣ urls.py // routing [ref](https://docs.djangoproject.com/ja/2.0/topics/settings/)<br>
&nbsp;&nbsp;&nbsp;&nbsp;┣ wsgi.py // entry point for web server [ref](https://docs.djangoproject.com/ja/2.0/howto/deployment/wsgi/)<br>
&nbsp;&nbsp;&nbsp;&nbsp;┗ __pycache__<br>
