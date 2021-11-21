# Elitmus-Assignment
This web application has one webpage where user can enter the link to get shortened link which is redirected to the same page.


INTRODUCTION:

•	Flask is a framework for building web applications using python.

•	SQLite is a Database engine that you can use to store application data.

•	Hashids is a library that generates a short Unique-ID from intergers.

•	Bootstrap toolkit is used to style your application.

![Screenshot 2021-11-21 at 12 58 49 AM](https://user-images.githubusercontent.com/94466436/142756768-d0d1cabf-97d8-4720-abd4-f3da98b963b2.png)



PREREQUISITES:

•	I used a local python3 in Virtual-Environment mode.

•	I run backend python code in Terminal(MacOS).



STEPS TO RUN THE ASSIGNMENT APPLICATION:

•	Create a folder for storing application files.

$ mkdir flask_project

$ cd flask_project

•	Creating Python3 Virtual-Environment files in the folder.

$  python3 -m venv myvenv

•	Activating the Virtual-Environment in the folder.

$ source myvenv/bin/activate

•	Install Flask and the Hashids library using the command:

$ pip install flask hashids

•	Download the all the programming files from this repository and move them to the application folder.

•	Create  a Database for the application using the following command:

$ python init_db.py

•	Set the environment variables Flask needs and run the application using following commands:

$ export FLASK_APP=app

$ export FLASK_ENV=development

$ flask run

•	Visit http://127.0.0.1:5000/ to open the web application.
