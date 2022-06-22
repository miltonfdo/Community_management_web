# Community_management_web
 
##Setting up the project:

This project is created on Python 3.10.2

### Step 1 : Setup python virtual environment

  Command syntax -> python -m venv <name_of_virtualenv>
  >Command -> python -m venv pyEnv

### Step 2: Activate the Virtual environment
 >Command -> .\pyEnv\Scripts\activate 


### Step 3: Install are dependent python packages
 > Command -> pip install -r requirements.txt


 ### Starting the project
 make sure to navigate to community_project folder(cd .\community_project)
 The first time we setup the project run the below commands
 > python manage.py migrate

 
 > python manage.py runserver


## Test user detatils
To create user for login ,run below command and answer questions
> python manage.py createsuperuser
> 
username- testuser
password - Passw0rd@01


To go to admim page - http://127.0.0.1:8000/admin/
Login page - http://127.0.0.1:8000/admin/login/?next=/admin/
  


How was the project setup
> django-admin startproject community_management_web
###Note:
 If any new package is being added newly in the project update the requitemnt.txt file, this can automatically be done by running below command
  >Command ->  pip freeze > requirements.txt