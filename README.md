# nearby

#django part

#how was project created

kedar : ~/Desktop/nearby
~$django-admin startproject nearby      ->used for creating a django project

~$cd nearby
~$ls
manage.py  nearby
~$python manage.py startapp backend ->used for creating apps in django project
backend  manage.py  nearby 
~$git init   -> used for initializing git

── nearby
    ├── backend
    │   ├── admin.py
    │   ├── apps.py
    │   ├── __init__.py
    │   ├── migrations
    │   │   └── __init__.py
    │   ├── models.py
    │   ├── tests.py
    │   └── views.py
    ├── manage.py
    ├── nearby
    │   ├── __init__.py
    │   ├── __pycache__
    │   │   ├── __init__.cpython-37.pyc
    │   │   └── settings.cpython-37.pyc
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    └── README.md

# repeat these three steps for running 
#step 1 and 2 are used when you change models in your app
python manage.py makemigrations
python manage.py migrate
python manage.py runserver

python manage.py createsuperuser
python manage.py shell

note : you are in nearby where there is manage.py ...then these codes will work

#for git  
->first open git and fork it
->clone your forked repo to your local machine
-> copy clone url
->git clone  'clone url'
example : git clone https://github.com/kedar170123023/nearby.git

->git remote add upstream https://github.com/kedar170123023/nearby.git





#some codes  to understand
git remote add origin https://github.com/yourusername/nearbygit
git remote add upstream https://github.com/originalpersonusername/nearbygit
git remote -v ->check  which are the remotes
git pull origin master ->used for fetching from your own repo
git pull upstream master    ->used for fetching from owner of repo
git status  ->used to check files status
git add . ->used for adding all files for staging
git commit -m 'commit message'  -> used to commit after changes 
git push -u origin master use this for pushing




git branch working ->used to create a branch named working
git checkout master -> switch to master branch
git branch  ->used to check all branches
git checkout -b feature  -> used to create a branch named 'feature' and switch directly to it
git pull origin master -> used to pull files from remote named origin to your 'master' branch
