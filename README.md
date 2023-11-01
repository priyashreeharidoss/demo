# PERSONAL BLOG ON IBM CLOUD STATIC WEB APPS

This personal travel blog that runs on IBM Cloud
How to run the project,
First download the personal travel blog folder
Inside that open the app.py file
To run the file, install ibm_db, flask using pip in python
Also create database in the cloud as follows
Steps to create DB2 in cloud
Select the DB2 service from the list of services available
Create a database instance
In that database, navigate to load data and upload the table structure as a csv format that is provided in the code and go to next step
Then create a table and edit the columns as required
Then finally the data will be loaded on to the cloud

Run using the command python app.py

1. Use the docker file in the folder
2. Built the docker image
3.Run the docker image
4.Use Kubernetes
5.Deploy in cloud


Navigation through the pages:

Initially when the code is run the home page will be displayed. The navigation bar is used to navigate between pages and it is present in all the web pages.

In the Navigation bar,
"HOME" links to the root of webpage ("/") i.e, home.html
"STORIES" links to "/travel" i.e, travel.html,
	When a particular destination from the image is clicked,it links to the blog page(eg."/taj" i.e, taj.html) related to that destination. 
"TRIPS & GUIDES" links to "/guide" i.e, guide.html,
	Images of various places that contain a guide will be displayed. When the image is clicked, the guide of the particular country(e.g "/india" i.e, india.html) will be displayed.
	Inside india.html under Top destination when a destination is clicked it links to the blog post related to that destination is displayed.
"GALLERY" links to "/gallery" i.e, gallery.html. 


 
