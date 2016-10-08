# CIS 322 Project 2 - Flask Basics

##Author: Alexander Dibb (adibb@uoregon.edu)

##Application Specifications

* The application returns a syllabus from a server-side file (schedule.txt) 
and formats it. It includes:
  * The week number.
  * The start date for that week.
  * A summary of the subject matter for that week.
  * A summary of the project for that week.
* The current week is highlighted on the syllabus.

##Running the Application

* The application may be run through the following commands:
  * git clone
  * bash ./configure
  * make run (debug) or make service (distribution)
* The default port is 5000.

##Testing the Application

* The contents of syllabus.txt may be altered to test different syllabi, from
subject matter to start dates, so long as the expected format is adhered to. 
* Alternatively, you may alter the code in the main function of pre.py to draw
information from a different file. Again, it should adhere to the expected
format.

##Disclaimer

This application was forked from the UO CIS 322 class project for week 2. The 
absolute majority of the code present is their work. If you have questions, you
will find more success looking to those working on that branch.

URL: https://github.com/UO-CIS-322/proj2-flask
they would be the ones to ask it of.