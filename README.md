# Eat-Da-Burger

## What is it Eat-Da-Burger?

Eat-Da-Burger was an exercise in utilizing the [MVC](https://www.tutorialspoint.com/mvc_framework/mvc_framework_introduction.htm) (or Model-View-Controller) architectural pattern. Each portion is designed to handle a different aspect of the application. 

## Getting Started

* ### Install Node Packages
    With npm installed, navigate to the directory with the package.json folder in your terminal and run the command:

    <code> >npm install </code>

    This will install all required node packages to run the program.

* ### Initialize/Seed the database
    Inside of the db folder lives the .sql files that will initialize your database. Run the schema.sql file first, and the seeds.sql file second.

* ### Add MySQL username and password
    Chances are you have a different username and password to access your MySQL databases. Navigate to the connection.js file inside of the config folder, and enter your username and password where necessary. Make sure you have connection running on local host before you start the server (next step).

* ### Run the server
    To start the server, navigate to the folder containing the server.js file, then run the command:

    <code>>node server.js </code>

    Note: you must have node js installed to run this.

* ### Navigate to the webpage
    In order to see web-page, go to your browser and type:

    <code>http://localhost:8080</code>

    and hit enter.

    Visit the deployed version here:

    https://aqueous-dusk-48426.herokuapp.com/