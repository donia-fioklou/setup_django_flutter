# setup django  flutter

## set up  django and django rest framework
### create virtual environment
- python -m venv .env
### active virtual environment
- source  .env/scripts/activate
### install django    
- pip install django
### install django rest framework
- pip install djangorestframework
### create project
- django-admin startproject project_name
### create app
- python manage.py startapp app_name

 after add the app and drf to the setting and configure database setting

## set up flutter
### create the project
 - flutter create project_name
### run flutter app wirelessly 
 - adb tcpip <port>
 - adb connect <device-ip-address>:<port>
 - default port : 5555




