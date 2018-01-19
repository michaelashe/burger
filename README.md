EAT-DAT-BURGER!!

"Eat-Dat-Burger" is an app designed to allow user input to add a data (in this case, a hamburger) to a mySQL database while also dynamically inserting data to the HTML page.

Using the submission form at the bottom of the page, a user can add a hamburger to the page.  That hamburger is added to the HTML page with a button next to it requesting the user to "Devour It".  Clicking the "Devour It" button not only commits it to the HTML page as a permanent fixture but also updates the mySQL database.

Due to the app being deployed to Heroku, it utilizes JawsDB (a cloud database service) to store our data.  The keys to access this database are in the .env file.
