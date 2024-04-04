# Ex02 Django ORM Web Application
## Date: 4.4.23
## reg no:212223240104
## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram

Include your ER diagram here

## DESIGN STEPS

### STEP 1:
Clone the problem from GitHub

### STEP 2:
Create a new app in Django project

### STEP 3:
Enter the code for admin.py and models.py

### STEP 4:
Execute Django admin and create details for 10 books

## PROGRAM
```
admin.py

from django.contrib import admin
from.models import Employee
admin.site.register(Employee)

models.py

from django.db import models
class Employee (models. Model):
    empid=models. IntegerField()
    empname=models. CharField(max_length=20)
    dept=models. CharField(max_length=20)
    salary=models. FloatField()
    aadhaar=models. BigIntegerField(null=True)
```
## OUT PUT
![Screenshot 2024-04-04 114933](https://github.com/feryjfgkuyfgewjfgew/ORM/assets/150319377/939df3e2-8f0c-41af-87db-823b71251885)

![Screenshot 2024-04-04 114917](https://github.com/feryjfgkuyfgewjfgew/ORM/assets/150319377/7ae70a02-ebce-4995-afea-69acec2efece)



## RESULT
Thus the program for creating a database using ORM hass been executed successfully
