# notes_App
Mini Project

creating project in mac os so commands that you see will be differ from windows

for Django:
 Install Python
 
 Intall django:
 pip3 install django 

 create a Project:
 django-admin startproject project_name

 Enter into the created project_name folder then start the server:
 python3 manage.py runserver

Now server will start with a generated link which you can access

create a app called api which is designated for writing APIs in it (make sure it is under the project_name folder)
python3 manage.py startapp app_name

now connect the newly created API to django core:
go to setting.py which is under project_name > project_name. Now search for key/varialbe INSTALLED_APPS.in that array add 

'app_name.apps.App_nameConfig' in it.