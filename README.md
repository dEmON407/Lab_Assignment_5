# Lab_Assignment_5

Installations: 
    pip
    django
    git
    
$ sudo apt install python3-dev python3-pip python3-virtualenv

Later run following command:
 $ python3 manage.py migrate

 Create a super user by:
 $ python3 manage.py createsuperuser --username admin --email admin@mail.com

 Run application:
 
To get the url enter following command
    $ python3 manage.py runserver
    copy url and run it on browser
    http://127.0.0.1:8000/sayHello
