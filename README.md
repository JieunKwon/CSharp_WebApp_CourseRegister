# CSharp_WebApp_CourseRegister
@ April 2019

Summary
-----

Create a Web Application, that allows users to search for Online Courses offered by an institution. 

Users can get the list of Courses and search for courses based on multiple fields.

Users request registration and view their registration status.

For the details, user can access users' page to manage their information such as My Order, My Account, and My Cart.

Before admin's accept user's request, user can withdraw their registration request.


Page Details
-----

1. Login

2. Membership Register

3. Search Course

4. Register Course

5. View Registeration Status

6. Admin - Accept or Reject user's registration


Database
----

User Account

Admin Account

Course and Course Details

Course Register


Class Design
----

UserAccount

Admin

Course

Register


Pages
----

 <b> Users </b>
 
index.aspx - intro page with login navigation 

UserRegister.aspx - user account registeration

CourseList.aspx - allow user search course with keyword

CourseRegister.aspx - choose course and request register course

MyBoard.aspx - my course page with details of registration


<b> Admin </b>

Login.aspx - admin authorization

RegisterList.aspx - list of user's request, allow searching and sorting with key

UpdateRegister.aspx - accept or reject action about request

