# Readme

# Registration Webapp:

* Navigate to Your Projects Folder.


## Setting Up Project:

* Create the folder where app will be created on the command line:

'''bootcamp@codexadmin-Inspiron-3543:~/Projects/$mkdir registration_numbers_webapp'''


* Setup an ExpressJS server:
  First create a package.json file by running the following command in the terminal:

    '''npm init -y'''



  Now create an index/app.js file to start the server by using the following command:

  '''touch index.js'''



  Now install expressjs and save it as a dependency usin the command:

  '''npm install express --save'''



  Now in the index.js create the server instance:


  '''var express = require('express');
  var app = express();



  var server = app.listen(3000, function () {

  var host = server.address().address;
  var port = server.address().port;

 console.log('Example app listening at http://%s:%s', host, port);

});'''



* Create a get route with a dynamic parameter and Use the HttpResponse object’s .send method to response to the browser:


app.get('reg_number/:number', function (req, res) {
res.send('req.params.number');
});



## What we can do with the app now:

  * should be able to type in a url:

   http://localhost:3001/reg_number/CY123345

  it should print CY123345 in the browser.


  
