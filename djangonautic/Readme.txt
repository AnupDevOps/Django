# Steps to create a Django Blogs 

###############################
Install Python and Django
###############################
Download the latest version of Python from the python.org and install it on the you local computer. 
once Python Download. 
Check Python version with below command in CMD. 
python --version
# output will be python version. 

Install Django using below command in CMD.
pip install django

Once installation is complete, check version of Django by below command. 
python -m django --version

##############################################
Create Django Project and runserver.
##############################################


#To create a Project in django, Run below command in the Directory in which you want to store your Project. 
Run below Command in CMD
django-admin startproject djangonautic

cd djangonautic
python manage.py runserver   # Run this command where manage.py file is there. 
 http://127.0.0.1:8000/
