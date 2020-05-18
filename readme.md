## Synopsis

This is the assignments repository for Coursera's Front-End JavaScript Frameworks Overview: Angular (https://www.coursera.org/learn/angular). Assignments are classified into their respective directories and you can find assignment instructions in the pdf file in each directory under the actual project folder. In order to run the assignments you will need Node JS and Angular CLI installed. After installation, go into the folder conFusion and run `npm install` to install all the depedencies. Please note this repository is only for the information/audit purposes, don't use it to copy the assignments if you're also taking the course.

## To simulate REST API for Assignment 4
You can serve REST content by installing  'json-server' using `npm install json-server -g`. After moving to 'json-server' folder in Assignment 4/conFusion in your terminal window, type the following at the command prompt to start the server. This will introduce a delay of 2 seconds before the server sends the reply to a request:
	`json-server --watch db.json -d 2000`

The json-server also provides a static web server. Any resources that you put in a folder named public in the json-server folder above, will be served by the server at the following address:
	http://localhost:3000/