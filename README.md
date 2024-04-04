# Ex02 Django ORM Web Application
## Date: 4.4.23
## reg no:212223240104
## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).

## Entity Relationship Diagram
![Screenshot 2024-04-04 183038](https://github.com/feryjfgkuyfgewjfgew/ORM/assets/150319377/02172c14-dc4a-4fd9-9ac5-a7c5d2bfcaf1)


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
from .models import Books,BooksAdmin
admin.site.register(Books,BooksAdmin)

models.py
class Books(models.Model):
  Book_id=models.IntegerField(primary_key=True);
  Book_author=models.CharField(max_length=20);
  Book_name=models.CharField(max_length=50);
  publication=models.DateField();
  price=models.IntegerField();
class BookAdmin(admin.ModelAdmin):
  list_display=("Book_id","Book_author","Book_name","publication","price");


```
## OUT PUT
![Screenshot 2024-04-04 184420](https://github.com/feryjfgkuyfgewjfgew/ORM/assets/150319377/a27b0051-048f-43bf-9a84-8fe11b850e75)

## RESULT
Thus the program for creating a database using ORM hass been executed successfully
