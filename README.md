
# Muscle Farm

[The live site can be viewed here](https://dashboard.heroku.com/apps/muscle-farm/deploy/github)

![Mutli Device Screenshot](https://github.com/johndbigboi/Muscle-Farm/blob/master/static/images/Multi-device.png)


Welcome to Muscle Farm, a recipe website dedicated for fitness fanatic who loves cooking. Wondering what to eat before or after a workout? Muscle Farm answers your problem with a wide range of healthy recipes where you can add, edit and delete recipes.

Food is your greatest ally for fitness success. Muscle built in the kitchen!

Thank you for visiting my Github page. I hope you enjoy reading about the project below. Please feel free to contact me for any questions and suggestions. You can message me through my Github page. 

## Contents:

* [Muscle Farm](#Muscle-farm)
* [UX (User Experience)](#ux-user-experience)
    * [Project Goals](#project-goals)
        * [Target Audience Goals](#target-audience-goals)
        * [User Goals](#user-goals)
        * [User Stories](#user-stories)
        * [Site Owner Goals](#site-owner-goals)
    * [User Requirements and Expectations](#user-requirements-and-expectations)
        * [Requirements](#requirements)
        * [Expectations](#expectations)
    * [Design Choices](#design-choices)
        * [Fonts](#fonts)
        * [Icons](#icons)
        * [Images](#images)
        * [Colours](#colours)
        * [Defensive Design](#defensive-design)
    * [Wireframes](#wireframes)
    * [Database Design](#database-design)
    * [Features](#features)
    * [Technologies Used](#technologies-used)
        * [Languages](#languages)
        * [Libraries & Tools](#libraries--tools)
    * [Planning and Testing](#planning-and-testing)
        * [Feature Testing](#feature-testing)
        * [Further testing](#further-testing)
        * [Validators and linters](validators-and-linters)
    * [Deployment](#deployment)
        * [The following steps were taken to deploy Muscle Farm on Heroku](#deploying-muscle-farm-to-heroku)
        * [Cloning Muscle Farm from GitHub to Run Locally](#cloning-muscle-farm-from-gitHub)
  * [Bugs](#bugs)
  * [Credits](#credits)
  * [Closing Notes](#closing-Notes)
  * [Disclaimer](#disclaimer)


## UX (User Experience):👍🏽

### Project Goals:

Muscle Farm is milestone project for Code Institute Data Centric Development module. The goal of this project is to showcase a wide range of easy to cook/prepare recipes where the user can access the recipes, submit, edit, and delete recipes. My goal was to create a website which will help people to choose what to eat for training days.

<strong>Muscle Farm</strong> is developed by using HTML, CSS, Jquery, Javascript, Python Flask and MongoDB for database.

#### Target Audience Goals:

* For health enthusiast who's looking for simple healthy recipes.
* For people searching for easy to make recipes.
* For people starting to train and no idea what to eat.
* For health enthusiast where they can share they favourite recipes.

#### User Goals:

As a User I would like to:

* Be able to register and submit recipes.
* Be able to see feedbacks for logging in and logging out.
* Browse recipes by category.
* Be able to browse and navigate information easily.
* Be able to edit and delete recipes.
* Be able to see feedbacks for submitting/editing/deleting recipes.
* Subscribe for a newsletter
* Interact with the website on both desktop browsers, tablet and mobile devices.
* Be able to inform user with error messages from connection issues with database
* Generate and attract fitness fanatics to submit recipes.


#### User Stories:

##### Mr. Columbu: 
* <em>"As a user when i search for pre or post workout recipes online im often redirected to a supplements shops website."</em>

##### Mr. Coleman: 
* <em>"As user i wanted to find a list of healthy recipes suited for my training. It would be nice an easy access website with search functionality."</em>

##### Ms. Cutler: 
* <em>"As a user and a personal trainer i wanted to share my knowledge on food preparation and recommend my clients a reliable website."</em>


#### Site Owner Goals:

Maintaining to be fit and whilst enjoying eating is a very difficult thing to do. the hardest part is choosing what to eat  
before and after your training that will give you energy throughout the day and still have some space for your favorite desserts.

* Highlighting the Pre and post workout meal is the most important fuel during training. 
* Spreading the awarness with nutrition is the most important part of fitness.
* Health enthusiast can share their favourite recipes.
* Simple UI and easy to use website to access all the recipes.

## User Requirements and Expectations: 🎯

#### Requirements:

*  Navigate the website with ease, and with fast loading time.
*  Search functionality for Pre and post workouts recipe.
*  Provide a simple and easy to use online recipes.
*  User can browse, submit, edit and delete recipes
*  Interact with a visually appealing website.

##### Expectations:

* The User Interface easy to navigate with search function.
* The website loads with sufficient speed.
* The content on the website renders correctly on desktop, mobile and tablet.
* Content is visually satisfying and informative.
* The user feel informed and satisfied with the informaton available.


## Design Choices: 🎨

The design of this website was inspired from [envato market](http://preview.themeforest.net/item/recipepress-food-recipes-premium-html-template/full_screen_preview/13308568?_ga=2.142281013.668936205.1595721833-1264852785.1594245682) and color theme from [Freepik](https://www.freepik.com/premium-vector/set-instagram-story-social-media-post-template-food-promotion_5563290.htm#page=3&query=food+background&position=26).

#### Fonts:


#### Icons:

All icons used in the  were taken from [Font Awesome](https://fontawesome.com/) and [flaticon](https://www.flaticon.com/).

#### Images:

All background and images were taken from [freepick](https://www.freepik.com/) and [alamy](https://www.alamy.com/). I used the [Pixlr](https://pixlr.com/) to edit the images for their own purposes.

#### Colours:

I used [this](https://coolors.co/fefefe-eee1c6-00471b-050100) colour palette from coolors.co. 

![color palette](https://github.com/johndbigboi/Muscle-Farm/blob/master/static/images/color-palette.png)

#### #eee1c6(Champagne):

![#eee1c6](https://via.placeholder.com/15/eee1c6/000000?text=+) `#eee1c6`
* Font colour of the Navbar.
* Background colour of all search bar.
* Background colour of buttons.

#### #00471B(Forest Green Tradition):

![#00471B](https://via.placeholder.com/15/00471b/000000?text=+) `#00471B`
* Font colour of the Title.
* colour of the border.


#### #050100(Rich Black):

![#050100](https://via.placeholder.com/15/050100/000000?text=+) `#050100`
* Font colour of the forms.
* Font colour of the search box.
* Font colour of the recipe.
* Background colour Navbar.
* Background colour Overlay.


#### #fefefe(White):

![#fefefe](https://via.placeholder.com/15/fefefe/000000?text=+) `#fefefe`
* Background colour of pages.
* Background colour of forms.

#### Defensive design:

* All forms handle empty input fields by warning the user and not permitting recipe submission.
* User is given a message/alert feedback for actions/errors.
* User is not able to break the site by clicking buttons out of the expected order.

## Wireframes: 🛠 

All wireframes were designed and produced using [Balsamiq Mockups 3](https://balsamiq.com/). link to my [Wireframes]().

## Database Design: ⚙️
Using MongoDB provides the use of NoSQL features i was able to map out the following collections.

### Data Storage Types:
The types of data that are stored in the MongoDB database.
* ObjectID
* String
* Array
* Binary

Recipes Collection:
**Title**|**Key in Collection**|**Data Type**
:-----:|:-----:|:-----:
Recipe Id|_id|ObjectId
Name|Recipe_name|String
Category|Category_name|String
Description|Description|String
Image|image|String
Prep time|Prep_time|String
Cooking time|Cook_time|String
Ingredients|Ingredients|Array
Instructions|Instructions|Array

Categories Collection:
**Title**|**Key in Collection**|**Data Type**
:-----:|:-----:|:-----:
Category ID|_id|ObjectID
Category|category_name|String

Users Collection:
**Title**|**Key in Collection**|**Data Type**
:-----:|:-----:|:-----:
User ID|_id|ObjectID
Email|email|String
Username|username|String
Password|password|Binary


View the schema templates for the database collections <a href="https://github.com/">here.</a>


## Features: 🎡

### Features that have been developed:

* Register an account, login & logout functionality.
* Search by category by clicking navigation links.
* Users are able to search recipes by recipe's name.
* Users message feedback when Login.
* Users message feedback when submit,edit and delete recipes.
* Recipes descriptions, preparation time and cooking time.

### Features that will be developed in the future:

* Users have personalised profile can edit and upload photos/avatars.
* Nutrition tables for calories,carbohydrates and proteins.
* Using users location to the nearest supermarket to buy recipes.
* Users opt-in to subscribe to the mailing list for the latest information.
* Email authentication/duplicates for registry and security.
* User can rate and leave reviews for new submitted recipe.
* Admin only recipe review to accept or reject recipe.
* Users access to workout programs  


## Technologies Used: 👨🏽‍💻

#### Languages: ⚙️

* [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML/)
* [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/)
* [JavaScript](https://www.w3schools.com/js/)
* [Python](https://www.python.org/)

#### Tools & Libraries: ⚙️

* [Visual Studio Code](https://code.visualstudio.com/)
* [MongoDB Atlas](https://www.mongodb.com/)
* [PyMongo](https://api.mongodb.com/python/current/tutorial.html)
* [Flask](https://flask.palletsprojects.com/en/1.1.x/)
* [Jinja](https://jinja.palletsprojects.com/en/2.11.x/)
* [jQuery](https://jquery.com/)
* [Git](https://git-scm.com/)
* [Bootstrap](https://getbootstrap.com/)
* [Font-Awesome](https://fontawesome.com/icons?d=gallery)
* [Animate.css](https://animate.style/)
* [CSS Gradient](https://cssgradient.io/)
* [TinyPng](https://tinypng.com/)



## Planning and Testing: 📝

As I planned and developed this website using Python and mongoDB database, I planned throughly and tested every line of the codes and made sure the codes were functioning properly, looking for errors and adjusting until the code ran without any issues. This process allowed me to learn more in depth on how to work codes with Python, mongoDB database and libraries of Flask and Jinja. 

### Feature Testing: 🎡 


<strong>Register an account,login & logout:</strong>

* <strong>Plan: 📝</strong>  The user needs to register first to enter the website to have full access of all recipes and be able to submit, edit and delete recipes. User needs email, username and password to register. for password stored in the database it needs to be properly hash for safety feature.

* <strong>Implementation: 🏭</strong>  The user registers email should be in the proper format. Usernames will be check if had a duplicate within the database, using flash message to alert if its already exist. password need to match the repeat password. Upon passing all the required field all will be stored in the database. From the Python Libraries, need to import <strong>session</strong> for the user login and <strong>bcrypt</strong> for passwords.

* <strong>Test: 🧪</strong> To test this feature, i had to create several accounts in order to test the registration process as planned, checking the values were passed & stored in the database. Using the registered account, by logging in and out are succesfully.

* <strong>Result: 🏆</strong> The test passed as the created test user accounts stored in the database with encrypted passwords and the user can login and log out into session without problems.

* <strong>Verdict: ✅</strong>  This test has passed based on the above criteria and notes.

<strong>Search menu and recipe's category filter:</strong>

* <strong>Plan: 📝</strong>  The user can use the search menu to search by recipe name or use the category menu to filter recipes by categories. By using flash, a message will alert the user if no recipe exist in the database. 

* <strong>Implementation: 🏭</strong>  To implement this feature, i need to use the "Get" and "Post" method to access the database to search for recipes name. To filter categories, i need to use conditional if statements and using "mongo.db.collection.find" to target ({"category_name": "category_name"}). If the search is unsuccessful, a flash message will alert the user "No results found."

* <strong>Test: 🧪</strong>  To test this feature, i searched each recipe either by a letter or by the full name of the recipe.

* <strong>Result: 🏆</strong>  The test passed for every search made.

* <strong>Verdict: ✅</strong>  This test has passed based on the above criteria and notes.

<strong>User access to submit,edit and delete recipes:</strong>

* <strong>Plan: 📝</strong>  This feature is largely the main focus in terms of demonstrating CRUD functionality. The user needs to login first before they can access the function of submitting, editing and deleting recipes.

* <strong>Implementation: 🏭</strong> To implement this feature, I need to create 3 routes for each step within the CRUD operation. For Submitting and editing a recipe i need to use the "Get" and "Post" method and using conditional If statements. For deleting a recipe i need to use mongo.db.collection.remove. All the 3 routes have a feedback message to inform the user.

* <strong>Test: 🧪</strong>  To test this feature, i created few test recipes which i submitted, edited and deleted.

* <strong>Result: 🏆</strong>  The test passed for every CRUD operation i did and the database was updated accordingly.

* <strong>Verdict: ✅</strong> This test has passed based on the above criteria and notes.

<strong>Recipe forms for Submitting and Editing:</strong>

* <strong>Plan: 📝</strong>  I needed to create a page with a form that will either submit or edit the recipe, has a table form for ingredients and instruction. prevents to submit the form if the fields are empty.

* <strong>Implementation: 🏭</strong> To implement this feature, i used bootstrap form with validation. The table form for ingredients and instruction, i used Jquery that will add additional lines for more text space and Jinja for the required values and names to update the database.

* <strong>Test: 🧪</strong>  To test this feature, i created few test recipe which i submitted, edited and deleted.

* <strong>Result: 🏆</strong> The test passed for every CRUD operation i did and the database was updated accordingly.

* <strong>Verdict: ✅</strong> This test has passed based on the above criteria and notes.


### Validators and linters:

* The HTML code was validated with: [W3C](https://validator.w3.org/)
* The CSS code was validated with:[W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
* CSS Lint VSCode extension
* [PEP8](http://pep8online.com) and AUTOPEP8
* The website was tested on the following browsers:
    * Safari
    * Google Chrome
    * Mozilla Firefox
    * Internet Explorer

### Further testing:

I asked my family and friends for any issues they could find and what the page looked and felt like on their mobile and desktop devices. All the issues they found were fixed and tested again.


## Deployment: 🚀

Muscle Farm was developed in Visual Studio Code, while Git and GitHub were used for version control and Heroku to host the repository.

### Deploying Muscle Farm to Heroku:

* 1: <strong>Create</strong> a requirements.txt file using the following command.
```bash
pip3 freeze > requirements.txt
```
* 2: <strong>Create</strong> a Procfile with the following command.
```bash
echo web: python3 app.py > Procfile
```
* 3: <strong>Push</strong> these newly created files to your repository.
* 4: <strong>Create</strong> a new app for this project on the Heroku Dashboard.
* 5: <strong>Select</strong> your <strong>deployment</strong> method by clicking on the <strong>deployment</strong> method button and select GitHub.
* 6: On the dashboard, <strong>set</strong> the following config variables:

**Key**|**Value**
:-----:|:-----:
IP|0.0.0.0
PORT|5000
MONGO\_URI|mongodb+srv://<username>:<password>@<cluster\_name>-qtxun.mongodb.net/<database\_name>?retryWrites=true&w=majority
SECRET\_KEY|"your\_secret\_key"
* 7: Click the deploy button on the Heroku dashboard.
* 8: The site has been deployed the Heroku.

### Cloning Muscle Farm from GitHub:

<strong>Ensure</strong> you have the following installed:
* PIP
* Python 3
* Git

<strong>Make sure you have an account at <a href="https://www.mongodb.com/">MongoDB</a> in order to construct the database.</strong>

<em>WARNING: You may need to follow a different guide based on the OS you are using, read more <a href="https://python.readthedocs.io/en/latest/library/venv.html">here.</a></em>

* 1: <strong>Clone</strong> the Muscle Farm repository by either downloading from <a href="https://github.com/johndbigboi/Muscle-Farm"> here</a>, or if you have Git installed typing the following command into your terminal.
```bash
git clone https://github.com/johndbigboi/Muscle-Farm
```
* 2: <strong>Navigate</strong> to this folder in your terminal.
* 3: <strong>Enter</strong> the following command into your terminal.
```bash
python3 -m .venv venv
```
* 4: <strong>Initilaize</strong> the environment by using the following command.
```bash
.venv\bin\activate 
```
* 5: <strong>Install</strong> the relevant requirements & dependancies from the requirements.txt file.
```bash
pip3 -r requirements.txt
```
* 6: In your IDE now <strong>create</strong> a file where you can store your SECRET_KEY and your MONGO_URI, follow the schema structure located in data/schemas to properly setup the Mongo Collections.
<em>NOTE: I developed this website on Visual Studio Code and used the following settings.json file, delete and replace with your values.</em>
```json
{
    "python.pythonPath": "env/bin/python",
    "python.terminal.activateEnvironment": true,
    "python.linting.enabled": true,
    "python.linting.pylintArgs": ["--load-plugins=pylint_flask"],
    "files.autoSave": "onFocusChange",
    "files.useExperimentalFileWatcher": true,
    "terminal.integrated.env.osx": {
      "SECRET_KEY": "<your_secret_key>",
      "DEV": "1",
      "FLASK_DEBUG": "1",
      "MONGO_URI": "<your_mongo_uri>"
    }      
}
```
* 7: Run the application using 
```bash
flask run 
```
or 
```bash
Python3 app.py
```


## Bugs: 🐞

#### Bugs During Development: 


Developing this project with being new to Python, flask and MongoDB, i encountered errors along the way that proved to be somewhat challenging and it took me 
longer to find solutions and fixes.

<strong>Array Issue for ingredients and instruction:</strong>

* <strong>Bug:</strong> 🐞 I developed a custom table form and the input was not registering on the database as an Array but as an Object.
 
* <strong>Fix:</strong> 🛠 As i'm new in using Python, flask and MongoDB, After a long-time of research, the code that i'm missing is request.form.getlist. The code will store the input on the database as an Array.

* <strong>Verdict:</strong> ✅ This bug was squashed and I could continue working on other aspects of the project.


## Credits: 💳

* I used [Stack Overflow](https://stackoverflow.com/) for guides in developing my own codes.
* Image for README.md multi device layouts taken from [techsini](https://techsini.com/multi-mockup/index.php)
* Image editor online [pixlr](https://pixlr.com/) and [imgonline](https://www.imgonline.com.ua/)
* Used to make favicon [Favicon Generator](https://www.favicon-generator.org/) 
* Used for color theme [Coolors.co](https://coolors.co/)
* Helps my project for height and width [Unicorn Revealer](https://chrome.google.com/webstore/detail/unicorn-revealer/lmlkphhdlngaicolpmaakfmhplagoaln?hl=en-GB)
* for css animation [Animate.css](https://animate.style/) and [CSS Gradient](https://cssgradient.io/)
* Big Thanks to Code Institute Tutors
* [freepik](http://www.freepik.com) images design by xamtiw and rawpixel.com


## Disclaimer:📃

Muscle Farm is developed for educational purposes only, and is not intended for use in any other capacity.

[Back to top ↑](#muscle-farm)
