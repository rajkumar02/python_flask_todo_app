Thrivia API
-----------

### Introduction

This is a simple **flask** todo application and backend connected with local postgreSQL database. That can handle all _ORDMS_. 

### Overview

Todo flask application. This application manage all CURD operation by using **SQLALCHEMY** and server using a PostgreSQL database:

* creating new todo.
* delete existing todo list.
* add sub listing.
* delete sub listing.

### Tech Stack

Our tech stack will include:

* **SQLAlchemy ORM** to be our ORM library of choice
* **PostgreSQL** as our database of choice
* **Python3** and **Flask** as our server language and server framework
* **Flask-Migrate** for creating and running schema migrations
* **HTML**, **CSS**, and **Javascript** for our website's frontend

### Development Setup

First, [install Flask](http://flask.pocoo.org/docs/1.0/installation/#install-flask) if you haven't already.

  ```
  $ pip install Flask
  ```

To start and run the local development server,

1. Initialize and activate a virtualenv:
  ```
  $ cd YOUR_PROJECT_DIRECTORY_PATH/
  $ virtualenv --no-site-packages env
  $ source env/bin/activate
  ```

2. Install the dependencies:

  ```
  $ pip install -r requirements.txt
  ```

3. Run the development server:
  ```
  $ set FLASK_APP=app.py
  $ set FLASK_ENV=development # enables debug mode
  $ python app.py
  ```

4. Navigate to Home page [http://localhost:5000](http://localhost:5000)

> If you like this project please give it to __star__. :star:

---

:octocat: Contact and give any feedback [Fcebook](https://www.facebook.com/itsrajkumar1)