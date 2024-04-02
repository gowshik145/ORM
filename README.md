# Ex02 Django ORM Web Application
## Date: 02-04-2024

## AIM
To develop a Django application to store and retrieve data from a Book database using Object Relational Mapping(ORM).


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
from .models import employee
admin.site.register(employee)

models.py

from django.db import models
class employee(models.Model):
    empid=models.IntegerField()
    empname=models.CharField(max_length=20)
    dept=models.CharField(max_length=20)
    salary=models.FloatField()


```

## OUTPUT

![Screenshot 2024-04-02 113822](https://github.com/gowshik145/ORM/assets/155086127/e751b287-db6e-47c3-9b1d-281e94b4b6a2)




## RESULT
Thus the program for creating a database using ORM hass been executed successfully
