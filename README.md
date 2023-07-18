# ONLINE VOTING SYSTEM 

---------------------------------------------
|Name|
|----|
|B. Venkata Sai|
---------------------------------------------
### FEATURES:

This online voting system has following features:

1. This system facilitates the Administration to
	* check out the statistics of the election scene
	* create and contest elections
	* change the election status to completed or running
	* add and remove candidates to the election system
	* facilitating them to appoint & reject to one or more election
	* choose specific voters for each and every election
	* allow & debar voters from casting their vote for one or more position
	* remove voters from the election system
	* view live election results
2. The Voters have the facility to
	* register themselves on the portal 
	* they will get a special encoded QR code for verification
	* caste their vote for more than one election
3. The Polling Agent can
	* check out the statistics of the voter
	* verify the details of the voter to check their genuinity
	* validate them to cast their vote.

---------------------------------------------
### ER DIAGRAM:
ER Model or Entity Relationship Model describes the structure of a database with the help of a diagram.
This is included in the directory with name "er_diagram.png"

---------------------------------------------
### TECHNOLOGY USED:

For developing this project we have incorporated the use of following technologies :
	* Backend : Node JS, Express
	* Frontend : HTML, Javascript, EJS

Along with this, we have also made use of some public libraries and Google Images to make our project more interactive and user friendly.

---------------------------------------------
### DATABASE:

For storing and fetching the data, we have used MySQL 8.0 .
The properties of the database we have used are as follows:

1. All the tables are normalized in Third Normal Form (3NF).
2. There is no repetition of data in the schema.
3. Incorportated the use of Primary Key and Foreign Key.

---------------------------------------------
### STARTING THE PROJECT:

This directory contains :
	* er_diagram.png
	* myapp.zip
	* query.sql

To run the project, you need Node.Js installed in your system.
Follow the following steps in the given order to run the application :

1. MYSQL:
	* Open MySQL
	* Open the query.sql file and run the commands to create the Schema dbms with predefined tables.
2. Nodeapp.zip
	* Extract the zip file in a folder and navigate into myapp folder where you can view all the files and folders.
	* Open the database.js file in a text editor and change the credentials of the database in it.
3. Node.JS Command Prompt
	* Open Node.JS Command Prompt and navigate it to the directory of Nodeapp.zip
	* Run command "npm install -g nodemon" to install npx nodemon which will help host the application on localhost
	* Run command "npx nodemon"
4. Browser
	* Run http://localhost:3000/ in your desired browser to start the online voting system.

Predefined Credentials:
1. Admin Page:
	* Username : admin
	* Password : pass
2. Polling Agent:
	* Username : agent
	* Password : pass
These credentials can be changed by accessing the 'admin' & 'agent' table respectively in the database dbms.

---------------------------------------------
