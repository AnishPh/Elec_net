# Elec_net
A online election system

Each user had to register once before the “Election day”. Each user was given a unique password (Private key) while registering. The password details and a confirmation link was sent by mail to the user. User can log in and has to wait for voting until the Election Day. On the day of the election, voting module would be enabled and user can vote. At the end of the day, all votes would be calculated and the winner of the elections would be declared the next day.
The website was hosted locally using a wamp server. Php MySql was used for the database connectivity.

A user could change his vote as the first time he may have been forced to vote. This additional feature  received a lot of praise at the same time was criticized as it wasn’t a biased option.

Technologies used:
HTML,CSS,JS, PHP, Sendmail, MySql, Wamp

	
Future implementations:
•	Collaborate with the government for using the Aadhaar Card database for validating users authenticity during the registrations.
•	It has also been suggested that the campaigning dates can also be displayed on the site.

FILESYSTEM
The main "home" directory is a base directory for this project.
Some of the file's purposes are explained.
admin.php
  This file contains the code for the admin console
  The admin console typically includes controls for changing election dates,allowing voters to participate and disable the voting module     after election is over.

Resource directory includes Base and Vote directory.
Base directory contains 
 The register directory contains resources used in the registration page.
 Other resources that are used by template.
 Phiosopher Bold and Philospher Regulare are the font varaints.
Vote directory contains:
  Files used in the voting page.
  

Steps to download/implement in your workstation
1)Install Wamp server 
2)Install Notepad++
3)Go into www directory of wamp.(wamp's default directory is in C/programfiles/wamp, unless you have changed it during installation.wamp and wamp64 refer to the same directory.(32 bit or g4 bit))
4)Paste this Elec_net directory in www directory.
5)Start your wamp server.
6)Start your browser(Preferred:Chrome) and go to your localhost site.
7)Change the url to localhost/Elec_net/home/index.php.
8)Now open your phpmyadmin console of the wamp server.
9)Create a new database named 
  
  
  

  
