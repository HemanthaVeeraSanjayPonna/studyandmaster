# studyandmaster
http://studyandmaster.cloudns.cl/

* This project is a java web application developed
using MVC architecture completely built from
scratch for online courses. 

* Passwords stored in database are encrypted using PBKDF2 with
HMAC-SHA1 algorithm.

* Database connection Pool is used in order to handle more requests. For
Front-end styling Bootstrap is used.

* Users can take Quizzes and get course completion certificate
which contains their score and number of passing attempts in 
pdf format.

* Database used in this project is clearDB MySQL of Heroku Cloud. For
certificate PDF generation itextpdf is used.

* Deployed on AWS EC2 Server and mapped domain on ClouDNS.
