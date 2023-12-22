Deleting Process is 

1. Select the model from specific appication and remove from the models 
2. Now remove the all the connections where you connected like registered in admin
3. Come to CMD, migrate the specific application for permanent changes in database and ORM.
    Syntax:  python manage.py migrate {specific_app name write here}
             python manage.py makemigrations {specific_app name write here}
             python manage.py migrate {specific_app name write here}
4. Now check once in admin interface.
5. Take a look on applications>migrations : 0001_initial.py 
    From the py file only existed operations done and stored.