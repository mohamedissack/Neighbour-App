# Neighbourhood Watch

## Author
Mohamed Issack Abdi

## Description
A website to keep a user in the loop about everything happening within their neighbourhood.
## Set Up and Installations

### Prerequisites
1. Python version 3.8
2. Django 
3. Pip
4. Virtual Environment(venv)


### Clone the  project 
Run the following command on the terminal:
`git clone https://github.com/mohamedissack/Neighbour-App.git`


###  Project Setup
1. Create virtual environment (python3 -m venv virtual)
2. Activate virtual environment (. virtual/bin/activate)
3. Install  all dependancies ( pip install -r requirements.txt)
4. Create database (CREATE DATABASE hood;)
5. Make migrations

#### Database Migrations
    python3 manage.py makemigrations neighapp
    python3 manage.py migrate

6. Run the application
    ### Run
    python3.8 manage.py runserver

7.  Testing the application
     python3 manage.py test neighapp