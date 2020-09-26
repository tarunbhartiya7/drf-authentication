# How to start project
source env/bin/activate 
cd nestedSerializers
python manage.py runserver

for permissions create superuser
python manage.py createsuperuser

user credentials
tarun/Django@123

# Difference etween authentication and authorization
authentication is only  allowing valid users to login to theapplication
authorization is after logging in whether the user is allowed to acceess a
particular resource or not. What operation can the user perform.