CabsOnline Web Application (R) version 1.0 24/04/2013

DECLARATION
-----------------------------
This application is an academic work of Vivek S Patil, Student ID : 1784765 studying at Swinburne Unversity of Technology, Hawthorn.
This application is developed as a part of Assignment1 of Web Application Development unit.

GENERAL USAGE NOTES
------------------------------
1. CabsOnline Web Application is a web application, used to book cabs online.
2. Customers need to register themselves by providing details like Name, Email address, Password and Phone number.
3. An email to the customers' registered email address is sent to notify about successful registration of a customer.
4. Customers can then login into the CabsOnline using registered Email address and password to book a cab.
5. While booking the cab, the pickup date and time should be later than 1 hour of the current date and time.
6. The dates must be provided in 'DD/MM/YYYY' format and time 'HH:MM'(24-hour) format.
7. Administrator is provided with a default email address and password for CabsOnline application.
8. The registered email address of admin is : 'admin@cabsonline.com' and password id '12345'.
9. Admin can view the booking details of the pickups which are between the current time and 2 hours later.
10. Admin can assign the cabs for the bookings based on the booking reference number.

Highlighted: 

email address of admin is : 'admin@cabsonline.com' and 
			  password is : '12345'

PACKAGE CONTENTS:
--------------------------------
The CabOnline.zip package consists of 7 files,
1. login.php
2. register.php
3. booking.php
4. admin.php
5. Cabsonline_Style.css
6. WAD_DB_Scripts.txt
7. ReadMe.txt

IMPLEMENTATION NOTES:
--------------------------------
The application is developed using HTML, CSS, PHP and SQL languages.
MySQL database is used to store the booking and user information.
QueryString technique is used to transfer the customer number from login page to the booking page.
HTML hidden field is used to store the customer number in the booking page.
CSS is used to the minimal extent to style the heading.
Database concepts like data integrity is maintained using primary and foreign keys between the customer and the Booking table.

OPERATING ENVIRNOMENT:
-------------------------------
The application is build for demonstration of skills in PHP and mySQL, So it can not handle concurrency access.
Security is not at the highest level.

CONTACT INFORMATION
---------------------------------
For any feedback, report, suggestions please contact
Vivek S Patil
SID : 1784765
Email : 1784765@student.swin.edu.au
Mobile: 0424-485-291
