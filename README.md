# django2024

## create virtual environment
	```python -m venv venv```
# 👇️ activate on Windows (cmd.exe)
	```venv\Scripts\activate.bat```

## install django: 
	```pip install django```
	
## create a new project
	```django-admin startproject student_management_project```
	
## run test
	```
	cd student_management_project
	python manage.py runserver <Tên Cổng>
	```
	
##  create the app
	```python manage.py startapp student_management_app```
	
## migrate your models into the database
	```
	python manage.py makemigrations
	python manage.py migrate	
	```
	