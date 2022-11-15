# DjangoFirstProject - Continuous Assessment 1
On this Assessment I have been following along "docs.djangoproject.com",
in order to create my first django project.

You can run the command 
`git clone https://github.com/sbritobreno/DjangoFirstProject.git`, somewhere
in your computer, before running the program you have to first change a few 
settings on the database(`djangoproject/settings.py line 79`), adding you own settings and also creating a database
in mysql with workbench or command line(query = `CREATE DATABASE databaseName`),
also before running the program you have to run the command `py manage.py createsuperuser 
in order` to create a user to use the program properly and also run the command
`py manage.py migrate` to load the changes from the database settings, after that you can run the command 
`py manage.py runserver` to finally run the program, then you can go to your browser
and access the `localhost:8000/` URL.

This simple program allows users to create polls and let people voting as many times they want,
it also has a login/logout functionality which also checks if the users is log in,
and store it in the database along with all the poll questions and choices, I have 
also added an .css file to stylize all the pages.

