# django_polls
Polls Web Application, vote on questions
Users will be able to vote on their favorite choices 

# Setup
after downloading repository go into the mysite directory from the directory you have downloaded the repository in with the command

```bash
cd mysite
```
if you run 
```bash
ls
```
you should see a "manage.py" file, a "mysite" folder, a "polls" folder, a "templates" folder, and a "db.sqlite3" file

next, to start the webapp you can run 

```bash
python manage.py runserver
```

now it will start the webapp at http://127.0.0.1:8000/

# Usage
to see index of 5 most recent questions, use extension 'polls/' (http://127.0.0.1:8000/polls/)

if you click on the question it will take you to the question detail page where you can vote on the options displayed

once you click on an option and press the "Submit" button, you will be redirected to a page that shows you the results of the quesion (how many votes each option got)

# Enjoy!! :)



