# Utmost-Pitch-App



## By victor

> This is a Flask application that allows users to submit their one minute pitches and other users to vote on them and leave comments of their feedback on them. The pitches are organized by category. 

### Screenshot of the App


## Table of Content

+ [Description](#description)
+ [Setup/Installation Requirements](setup&installationrequirements)
+ [How To Access the Site](#howtoaccessthesite)
+ [BDD & TDD](#bdd&tdd)
+ [UserStory](#userstory)
+ [Technology & Tools](#technology&tools)
+ [Reference](#reference)
+ [Known-Bugs](#knownbugs)
+ [Licence](#licence)
+ [Authors Info](#authors-info)

## Description

> This is a Flask application that allows users to submit their one minute pitches and other users to vote on them and leave comments of their feedback on them. The pitches are organized by category. 



## Setup/Installation Requirements

### You need to have the following installed

#### Prerequisites

You must have git, flask, postgres and python3.8+ installed in your pc.
To install flask and Postgres, you can use the following commands:

```
#flask
$ pip install flask

#postgres
$ sudo apt-get install postgresql postgresql-contrib libpq-dev
```

```
 
1.Download and install Git by writting the above ($ sudo apt install git-all)
  Clone this [github repo] ()
2. Ensure python is installed on your machine($ sudo apt-get install python3.8)
3. On the terminal for linux or command prompt for windows;
  * Open the containing folder by cd.
  * Run $ chmod +x start.sh
  * Run the application: $ ./start.sh

```

### Deployment environment
* Heroku

### How To Access the Site
> This App is being hosted by GitHub Pages. The link to the live site is: https://utmostpitches.herokuapp.com/


## BDD
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Display the pitches categories. | **On page load** | Each category can be viewed on click |
| Authentication Required | **Add New Pitch** | Redirected to a Login/Registration Page |
| Display form where one can add comments  | **Add Comments** | Redirected to view Comments Page |
| Display Profile of User | **Click User Profile** | Redirected to Update Profile Page



## TDD

> To test the app, run this command in the terminal;

`$ python3 manage.py test`


## User Story
* A user can see the pitches other people have posted. - Achieved
* A user can be signed in and leave a comment -Achieved
* A user can vote on the pitch they liked and give it a downvote or upvote. -Not Achieved
* A user will receive a welcoming email once they sign up. - Not Achieved
* A user can view the pitches they have created in their profile page - Achieved
* A user can comment on the different pitches and leave feedback - Achieved
* A user can submit a pitch in any category. - Achieved
* A user can view the different categories - Achieved

### Technology & Tools
* Python
* Flask
* HTML
* CSS
* Bootstrap
* Postgres

## Reference

* [Setting up Postgres, SQLAlchemy, and Alembic](https://realpython.com/flask-by-example-part-2-postgres-sqlalchemy-and-alembic/)
* [Flask for Beginners](https://www.fullstackpython.com/flask.html)



## Known Bugs
> Some bugs on the tests were not fixed (Bug not fixed) . Know how to Debug it ? Feel free to reach me Asap!

## License

> [MIT License](license) this application's source code is free for any open source projects

> Copyright (c) 2022 **victor**



## Authors information
> Feel free to add your contribution to the code.

> If you have any questions,comments or advice,feel free to contact me

* [Email]()
* [LinkedIn]()
