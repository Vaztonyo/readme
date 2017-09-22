# Checklist For Registration Number Webapp:


* Navigate to Your Projects Folder.


## Setting Up Project:

* Create the folder where app will be created on the command line.


* Setup an ExpressJS server:
  First create a package.json.


  Now create an index/app.js file to start the server.


  Now install expressjs and save it as a dependency.


  Now in the index.js create the server instance.


* Create a get route with a dynamic parameter and Use the HttpResponse object’s .send method to response to the browser.



* Add a ExpressJS middleware to serve client side files such as CSS & JavaScript using express.static middleware




## Use Handlebars as the view engine:

* Reference the Handlebars library.

* Configure Handlebars as a view engine in ExpressJS.     Using the express-handlebars module.

* Create a views folder in your project directory.

* Create a layouts folder in the views directory to set your main layout.

* Create the main page with the handlebars file extension.

* Use handlebars({{}}) to render information from the data in the main.js.



## Registration number form & list:

* In the app.js create a:

    "A GET route called /reg_numbers" &
    "Add a POST route called /reg_numbers"

* ExpressJS

    "Adding HTTP POST routes."
    "Adding middleware to allow form parameters to be read from the HttpRequest object in your route."
    "Storing a data in a global variable in ExpressJS."
    "Create & render data using Handlebars."

* Handlebars

    "Render a list of data into HTML."
    "Combine various different HTML elements and Data Types using Handlebars."


## Registration numbers for selected town:

* Create a function that filters the numbers so that one is able to display number for a selected town.
