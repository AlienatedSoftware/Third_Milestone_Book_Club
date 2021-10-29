# Aidan's Arcade

## Code Institute: Milestone Project 3

![Mockup](media/responsive.PNG "Mockup")

https://flask-book-club-project.herokuapp.com/

## IMPORTANT

To check with admin unique controls of controlling book categories, you must login as a admin.

User: admin
Password: Admin

Ensure that the password has the capital 'A'

## Table of Contents

1. [Introduction](#Introduction)
2. [UX](#UX)
    1. [Ideal User Demographic](#Ideal-User-Demographic)
    2. [User Stories](#User-Stories)
    3. [Development Planes](#Development-Planes)
    4. [Design](#Design)
3. [Features](#Features)
4. [Technologies Used](#Technologies-Used)
     1. [Programs Used](#Programs-Used)
     2. [Frameworks & Tools Used](#Frameworks-and-Tools-Used)
5. [Testing](#Testing)
6. [Deployment](#Deployment)
7. [Acknowledgements](#Acknowledgements)
***

## Introduction

Book Club -  Backend Development - Code Institute

The goal of Book Club is to welcome all book worms alike to join together as a little community to share our books together, and recommend others to read what you love!

Book Club was created with witty indivuals in mind, who like to socialise and is not afraid of sharing ideas. Most of these users will be mobile users on the go, in a book store or on a train! However this website is highly optimised for desktop users too.

This project follows a CRUD (Create, Read, Update and Delete) system.

It has a clean, simplistic and minimal design to not make the screen too distracting, so the users will be greeted with book titles, and an easy to use navigation system.

This is my third of four Milestone Porjects that I must complete during the Full Stack Development Program over at Code Institute.
The primarily requirements for this milestone is to make a backend development website with the use of **HTML, CSS, JavaScript, Python+Flask, MongoDB**.
***

## UX

### Main Objectives

- Allow users to choose create, read, update and delete posts. Project must meet a CRUD system.
- Simplistic and easy navigation.
- To create an virtual book club that is responsive to handheld devices.

### Ideal User Demographic

The ideal users of this website are:

- Students
- Adults
- Eldery

### User Stories

The ideal user of this application would be someone who absolutely loves to read books, but doesn't have access to a local book club to interact or share with others about what they enjoy to read. This project aims to satsify those users who miss out on book clubs and to be welcomed to a virtual one.

#### Students

1. As a Student, I want to explore the enjoyment of the minds of writers and exploring a new world of stories.
2. As a Student, I want a great introduction to books by getting recommendations from a mature audience.

#### Adults

1. As an Adult, I want to expand my collection on my bookshelf.
2. As an Adult, I want to seek out new chapters in life and seek inspiration.

#### Eldery

1. As an Eldery, I want to share with the world all the books I love to talk about with friends.
2. As an Eldery, I want to be able to explore the new generations of world building through books.

### Development Planes

In order to create an engaging website, the developer used their own passion for books to help create a simplistic, and fast design for a virtual book club.

#### Strategy
This website will be focused on the following target audiences:
- **Roles:**
     - Students
     - Adults
     - Eldery

- **Demographic:**
     - 13 - 70+ year olds
     - Students - Eldery
     - Book Community

- **Psychographics:**
     - Personality & Attitudes:
          - Youthful
          - Adventureous
     - Lifestyles:
          - Modern
          - Geeky
          - Bookworm

#### Home Wireframe
![home](media/Home.PNG)

#### Login Wireframe
![login](media/login.PNG)

#### Add Book Wireframe
![add_book](media/add_book.PNG)

#### Manage Categories Wireframe
![manage_categories](media/manage_categories.PNG)

###  Design

#### Colour Scheme

The main colours used throughout the website are a mixture of Purple and White, with some red for buttons. All used with Materialize default colours for simplistic and slick design.

#### Imagery

The logos are all from [Font Awesome](https://fontawesome.com/).
***

## Features

### CRUD System

- Allows users the ability to Create, Read, Update and Delete posts from within the database.

### Navigation Bar

- Clickable which will always take you to the home page. Responsive for mobile design that turns into a side navbar.

### Home

- Home screen consists of the shared books that has been recommended by users of the project.

### Login + Register Screens

- Responsive pages of forms to create/login to your personal accounts which will be held as data in the database.

### Share Book

- Responsive page of a forms to share a book that you like with the rest of the users/community.

### Manage Categories

- An admin only page to manage, edit or delete new categories for users to share books for.

### Features to Implement in the future

- A built-in feature to prevent security breaches to allow any user to access admin only content.
- A more fluid responsive design for smaller devices with buttons.
***

## Technologies Used

### Programs Used
- [HTML5](https://en.wikipedia.org/wiki/HTML5 "Link to HTML Wiki")
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets "Link to CSS Wiki")
- [JS](https://en.wikipedia.org/wiki/JavaScript "Link to JS Wiki")
- [Python](https://en.wikipedia.org/wiki/Python_(programming_language) "Link to Python Wiki")
- [MongoDB](https://en.wikipedia.org/wiki/MongoDB "Link to MongoDB Wiki")

### Frameworks and Tools Used
- [W3C Markup Validation Service](https://validator.w3.org/) - Used to check the validity and efficiency of the HTML and CSS code base.
- [Flask](https://en.wikipedia.org/wiki/Flask_(web_framework) "Link to Flask wiki")
- [PyMongo](https://docs.mongodb.com/drivers/pymongo/) - Used as drivers for Python to connect and work with MongoDB
- [Materialize](https://materializecss.com/ "Link to Materialize page")
     - Materialize was used to implement the responsiveness of the site, using Materialize classes, and to add many features.
- [Font Awesome](https://fontawesome.com/ "Link to FontAwesome")
     - Font Awesome was used on all pages throughout the website to import icons for UX purposes.
- [Git](https://git-scm.com/ "Link to Git homepage")
     - Git was used for version control by utilising the GitPod terminal to commit to Git and push to GitHub.
- [GitHub](https://github.com/ "Link to GitHub")
     - GitHub was used to store the project after pushing
- [Heroku](https://heroku.com/ "Link to Heroku")
     - Heroku was used to deploy the project
- [Am I Responsive?](http://ami.responsivedesign.is/ "Link to Am I Responsive Homepage")
     - Am I Responsive was used in order to see responsive design throughout the process and to generate mockup imagery to be used.
***

## Testing

Based on the User Stories above, all users will be able to follow the flow of the website to find what they came for according to their stories.

Google developer tools was used manually to check and test the live project on all different screen sizes. Used multiple devices and feedback from family & friends who went to the deployed site on their devices.


### UX Test for both Mobile & Desktop

[Mobile](https://youtu.be/67SZCd8ntxQ)

[Desktop](https://youtu.be/U6o6Q99XF08)
***

## Deployment

This website was developed in multiple editors, Gitpod and vsCode, and version controlling was utilised via local (git) and online (github) repository technologies, then deployed on Heroku.

### Deploying this application was achieved through Heroku by;

1. First create env file where you will put:
- Import os
- IP set on 0.0.0.0  or your own
- MONGODB_NAME Name of your MONGODB collection
- MONGO_URL link to your MONGODB cluster - to do this you have to open your mongodb > go to Clusters> under your Cluster name click the button connect, then choose Connect your application. Choose the second option which is add your connection string. Copy your string in the field.
- SECRET_KEY - set it as the most difficult key what you can think about, I used for that page [Randomkeygen](https://randomkeygen.com/)
- PORT set as 5000 or as you want

your env.py should look like :

import os

os.environ.setdefault("IP", "0.0.0.0")
os.environ.setdefault("PORT", "5000")
os.environ.setdefault("SECRET_KEY", "yourkey")
os.environ.setdefault("MONGO_URI", "yourcluster")
os.environ.setdefault("MONGO_DBNAME", "book_club")

2. We need a requirments.txt to satisfy heroku you need to create your requirments.txt with pip freeze --local> requirements.txt
3. Create a simple text file named Procfile without the file extension, ie Procfile.txt is not valid
4. Open procfile and tell heroku how to run the website by writing there python3 app.py
5. Open heroku Website,From there you have to create new app and open it
6. Go to settings, There u have to set the Config Vars.Set the:  IP, MONGODB_NAME, MONGO_URL, PORT, SECRET_KEY.

Your settings should look like:
- IP : 0.0.0.0
- MONGODB_NAME : Name of your collection in Mongodb
- MONGO_URL : url for your cluster
- PORT : 5000
- SECRET_KEY : your secret key

7. Since you did every step from before you can go to deploy section in heroku, scroll down and connect app to the github, click enable automatic deploys.
8. At the bottom of the page, click on Deploy Branch, make sure the master branch is selected

1. IP and PORT - IP address identify a host/computer on a computer network. Port numbers are logical interfaces used by communication protocols
2. MONGODB_NAME - Name of yours mongodb collection
3. MONGO_URL - URL connecting to your MONGODB cluster
4. SECRET_KEY - It is the security key 

### To clone the website:

Select the Repository from the Github Dashboard.
* Click on the "Clone or download" green button located above and to the right of the "Add file" button.
* Click on the "clipboard icon" to the right of the Git URL to copy the web URL of the Clone.
* Open your preferred editor/IDE and navigate to the terminal window.
* Type `git clone <paste-clone-url-here>` and press "Enter/Return" on your keyboard.
* This will create a clone of the project for you.
***

## Acknowledgements

All credits & References go to Tim Nelson of [Code Institute](https://codeinstitute.net/) for his mini-project walkthrough which greatly helped make this project possible and taught me advanced level backend development.

Thank you to my mentor, and all students over on the slack community for code insitite for all the helpful tips given to tackle my work.