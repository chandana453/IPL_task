
This is the implematation of Djnago api with couple of tasks based on the data reagarding to IPL match.its run under Djnago 3.1.1 and python 3.7 versions.

Please follow the below steps to create the Djnago project:

Step 1: Go to the command prompt
Step 2: for creating project run the command  "django-admin startproject Your_project_name"
Step 3: for creating the app run the command "python manage.py startapp Your_app_name"


Directory layout:
Django Directory structure looks as follows:

csv_data
├──  __init__.py
├──  asgi.py
├──  settings.py
├──  urls.py
├──  wsgi.py
env
files
├──   migrations
├──   templates
├──_init__.py
├──   admin.py
├──  apps.py
├──  models.py
├──  tests.py
├──  urls.py
├──  views.py
manage.py
requirements.txt

Installation:
Clone this repository: git clone https://github.com/chandana453/IPL_task.git.
cd into conduit-django: cd csv_data
Install virtualenv.
Install Python 3.7
Create a new virtualenv called env as $ virtualenv2 --no-site-packages env
Set the local virtualenv toenv. as   .env/bin/activate


Then install the dependencies:
(env)$ pip install -r requirements.txt

Once pip has finished downloading the dependencies:
(env)$ python manage.py runserver

And navigate to http://127.0.0.1:8000/.

To upload the csv files try with the url http://127.0.0.1:8000/upload

To get the top 4  tems to win http://127.0.0.1:8000/pie-chart/ 

To get the maximum player of the match try with http://127.0.0.1:8000/maximum_player_match/

To get the maximum toss winner try with  http://127.0.0.1:8000/toss_winner/

To get the which team won the maximum matches try with http://127.0.0.1:8000/winner/ .















