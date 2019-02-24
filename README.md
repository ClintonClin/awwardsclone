# awwardsclone
 
###  Author
Clinton Okerio

### Description
awwards is a clone of the website Awwwards. It allows a developer to post a project he has developed and get it reviewed by other people.

### User Stories
1. View posted projects
2. Post a project to be rated or reviewed
3. Search for projects
4. View projects overall score
5. View my profile page

how to write locust tests in django### How to use
To use awwards, you must login/register. Once logged in, you will be able to see projects posted by other users.
You can add your own projects from your profile page to get them reviewed.
You also have the possibility to edit your profile and view your projects.


### Tech used
1. HTML and CSS
2. Python
3. Django
1. Postgres
1. Heroku for deployment

## Set up and Installation
### Prerequisites
You will need to install git, django, postgres and python3.6+  in your device.
To install these packages, you can use the following commands
```
#git
$ sudo apt install git-all

#python3.6
$ sudo apt-get install python3.6.

#django
$ pip install django==1.11.5

#postgres
$ sudo apt-get install postgresql postgresql-contrib libpq-dev
```

### Installation
1. To access this application on your command line, you need to clone it
`git clone https://github.com/ClintonClin/awwardsclone.git`

2. Create a requirements.txt in the root folder and copy the requirements above.

3. Install the required technologies with
`pip install -r requirements.txt`

4. Create a .env file and copy the .env code above

5. You can then run the server with:
`python3.6 manage.py runserver`

6. You can make changes to the db with
`python3.6 manage.py makemigrations clone`
`python3.6 manage.py migrate`

7. You can run tests:
`python3.6 manage.py test clone`

### License
Copyright (c) **Clinton Okerio**

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
 