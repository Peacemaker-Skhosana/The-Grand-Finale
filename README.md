# The-Grand-Finale
This is a clone of the popular video streaming site Netflix. Built using Django and uses the requests library to handle data from TMDB API.
Requirements
The user can perform the following functions:

A user can view the different movies and Tv shows that are available.
A user can view a description Of the movie and its current rating.
A user watch a trailer for a movie or a Tv Show.
Installation / Setup instruction
The application requires the following installations to operate:

pip
gunicorn
django
postgresql
requests
Technologies Used
python 3.9.6
Project Setup Instructions
git clone the repository
https://github.com/steve-njuguna-kDjango-Netflix-Clone.git
cd into Django-Netflix-Clone
cd Django-Netflix-Clone
create a virtual env
py -m venv env
activate env
env\scripts\activate
Open CMD & Install Dependancies
pip install -r requirements.txt
Make Migrations
py manage.py makemigrations
Migrate DB
py manage.py migrate
Run Application
py manage.py runserver
