# AED_FinalProject
FOOD DONATION SYSTEM

Food Donation System using Java Swing.

-------------------------------------------------------------------------------------------------------------------------------

Need to work on:
 
A running swing application that addresses the challenges outlined above at an ecosystem scale. 
A typical implementation must include the participation of 4 enterprises, 6 organizations, and 8 roles(minimum requirement).
A presentation that outlines details specific to the design and implementation of your solution. This must include, the definition of the problem you solved, players and their contributions, use cases, design, and implementation techniques followed.
You must explain why each enterprise is essential to delivering the total value as outlined in your problem statement.
A robust role-based authentication module with strong username and password capabilities.
A reporting module with a summarized view of the data in your system. This could include performance data. That is important at the system or network level.
A configuration module with test cases that will populate your model and show the correctness of your solution.
You might want to integrate the Faker Module For Random Data generation.
You are required to defend your solution through a 40-minute live presentation. This examination will include a detailed review of your code and the validity of your engineering techniques. 
This is a team project with up to 3 participants. However, each participant must be able to answer any questions in relation to the implementation of the project.

-------------------------------------------------------------------------------------------------------------------------------

Prerequisites

1. Install the NetBeans application.
2. Have all dependencies and packages installed.
3. Install the  MySQL  Workbench application

-------------------------------------------------------------------------------------------------------------------------------
Class Diagram-

-------------------------------------------------------------------------------------------------------------------------------
Sequence Diagram-


-------------------------------------------------------------------------------------------------------------------------------
Created Files

We have created 18 classes and multiple attributes in all of them.

-------------------------------------------------------------------------------------------------------------------------------

Steps to run the project on your machine

Install the NetBeans application.
Install the MySQL Workbench application.
Open a project by going into the Files option -> Open Project -> right click -> Run File.

-------------------------------------------------------------------------------------------------------------------------------

Getting into the Project

Food Donation System in NetBeans using Java Swing application. 
The Home page of the project gives a login option for each user.
(Select, Donor, DonorAdmin, Volunteer, PackagingAdmin, LogisticsAdmin, DeliveryEmployee, Recipient, RecipientAdmin, Admin ).

The project consists of 4 Enterprise:-
1. Donor Enterprise: -
It consists of the donor and the donor admin.
The Donor Admin can CRUD donor and manages all donation requests made by a donor.
A donor can make a donation request and can check their donation history 
They can create or update their profile.

2. Packing and Storage Enterprise: -
 It consists of the volunteer and the PackandStore admin. 
The PackandStore Admin can CRUD volunteer. 
Admin manages all recipient requests made by a recipient and also manages all the storage.
The volunteer can register and update their profile. 
They can submit a time slot they are available to work and can check in to pin their sign-in and sign-out date & times.

3. Logistics Enterprise:-
 It consists of the delivery employee and the Logistics admin.
 The admin can CRUD the employee details and assign them work.
The delivery employee can view their work history, get details of their upcoming assignment and submit their details to the recipient of their next assignment.

4. Recipient Enterprise:-
 It consists of the recipient and the recipient admin.
The recipient admin can CRUD the recipient.
 A recipient can make a request for a donation to their organization, check the approval status of their request, and see delivery details of the donation that is made to their organization.
The recipient can create or update their profile.

5. System admin(Individual Role):-
They can view all the changes that have happened so far
CRUD all the other admins.
 
----------------------------------------------------------------------------------------------------------------------

If you want to contact us, you can reach us at dongale.s@northeastern.edu / gangadia.m@northeastern.edu / fernandes.roc@northeastern.edu 

Thanks

Shubham Dongale(002791214)
Mahek Gangadia(002797094)
Rochelle Fernandes(002756922)
