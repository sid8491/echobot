# Heroku deployment

### Create virtual env :
* Go to desired directory
* virtualenv venv

### Install required libraries :
* using "pip install" 
* export the dependencies to requirements.txt using ----> pip freeze > requirements.txt
* prepare gitignore file to exclude cache, venv and credentials file
* make Procfile ----> web: gunicorn file_name:app_name

### Push to heroku
* heroku login
* git add .
* git commit -m "msg"
* heroku create
* (optional) heroku open (to open the app in browser)
* git push heroku master


********** end **********