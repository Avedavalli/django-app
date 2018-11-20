# django-app
Welcome to the django-app wiki! The first page shows two buttons one is django which generates the form using the imported django form classes and the template tag is used to display the form in html page.csrf token is for security from cross site forgery. 
The second button displays as usual html form. In the templates folder the htmltemplates are placed and the static folder the static cssfiles,images are placed. 
The settings file and urls are configured accordingly.In the settings.py the template dir,and static dir were included. 
The model class is written and it is registered with admin.py.python manage.py migrate has to be applied .
The superuser can be created with python manage.py createsuperuser command with credentials and can access the admin page. 
The model class has integerfield,char field,datetimefields etc for creating the table.when the model class gets modified then migrations are to be applied.
The command is python manage.py makemigrations,This generates a .py file with some label name.
For sqlmigrate use migrate python manage.py sqlmigrate applicationname <application label>.This creates a profile(i.e the table ) and this can be viewed in admin page finally the python manage.
  py runserver command runs the server and by typing the localhost adress port in browser the application runs
