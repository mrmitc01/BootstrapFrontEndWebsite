BootstrapFrontEndWebsite

This code is used to implement the front end of a website with Bootstrap and light and dark themes

The purposes of each of the following files are stated below:


login.html - the login page, which contain a login form that accepts a username and password combination

new.html - the sign up page, which contains a sign up form that accepts a username, email, password, verified password, and phone number

user.html - the account page, which includes a form with the current logged in user's information

main.scss - contains the implementation for the light and dark themes

main.css - the code from main.scss converted to CSS


To convert the code from main.scss to CSS after any changes have been made to main.scss, type the following at the prompt >: 
> node-sass main.scss main.css

To run the above command, Node.js will need to be installed, which can be downloaded from: https://nodejs.org/en/.

Additionally, the Node-sass library will need to be installed, which can be done by typing the following at the prompt >:
> npm i -g node-sass

To switch between the light and dark themes, modify the body tag in login.html, new.html, and user.html to be either <body class = "light-theme"> or <body class = "dark-theme">

Run the source code by opening the login.html file in a web browser

Code is available upon request