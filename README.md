# blood-bank-management-system
1. INTRODUCTION:

BLOOD BANK MANAGEMENT SYSTEM is a software application to maintain day to day transactions in a blood bank. This software help to register all the donors, Blood collection details, blood issued details etc. The main objective of this application is to automate the complete operations of the blood bank. They need maintain hundreds of thousands of records. Also searching should be very faster so they can find required details instantly. The software product to be produced is a BBMS which will automate the major Blood Bank operations. The first subsystem is adding Donor Details and keeping track of Blood Stock availability in the Blood Bank. An efficient blood bank management system should be developed, with the aim of ensuring that every patient has access to an adequate quantity of safe blood in a centralized manner. The management system should solve the issue of demand and wastage and lead to self-sufficiency in blood requirement. This should encourage new donors and retain old donors to donate blood.

2. ABSTRACT:

The main goal of the Blood Bank and Donor Management System project is to monitor Blood Bank data, Blood cells, Blood stock, Donor List. It manages all the Blood Bank, Donor, and Blood stock data. The project is entirely administrative and therefore access is guaranteed only to the administrator. The project's aim is to develop an application system to minimize the manual work for Blood Bank, Donor, Blood Group management. It monitors all of the Blood Group information, Blood supply and Donor list.




3. SOFTWARE REQUIREMENTS:

1. XAMPP.
2. VISUAL STUDIO CODE.



4. PROGRMMING LANGUAGES USED:

FRONT END: php, html, CSS, java script.
BACK END: MYSQL.




5. ER-DIAGRAM:


Entity-Relationship Diagram is a graphical representation and relationship between entities. It describes the relationship between data.  An  entity  is  a  piece  of  data—an  object  or  a definition  that  stores  data  about.  Whether data is exchanged between organizations is a partnership. 



![image](https://user-images.githubusercontent.com/66869358/173079972-af6ca230-1275-447e-9c07-1752752a5c79.png)
 
 
6. TABLES:


![image](https://user-images.githubusercontent.com/66869358/173081023-0613288e-1171-4a6a-b3ff-c4c0becfdb60.png)


![image](https://user-images.githubusercontent.com/66869358/173081324-955625a5-0f0a-488f-8491-c89cf1b9a9e9.png)


![image](https://user-images.githubusercontent.com/66869358/173081428-f4450593-c61c-4284-8753-5e77c8c710b8.png)



7. ALGORITHM:

•	  Create a database and name it ‘bbms’ using mysql programming language.
•	Create tables in database admin, blooddonors, bloodgroup, contactusinfo,  contactusquery,          pages.
•	Add entities to all the tables . 
•	Now  we need to create front end for the project this is done using html and php languages.
•	We need 2 portals. 1. USER PORTAL  2. ADMIN PORTAL.
•	User portal has 6 sub pages one is a home page for users to visit or it’s the index page.
•	Second is ‘about’ page that displays briefs  about blood banks
•	Third is ‘why become  donor’ page that signifies the importance of blood donation.
•	Fourth page is the ‘become a donor’ page where the user can enter all his personal details if he/she  decides to become a blood donor.
•	Fifth page  is the ‘search for donor’ page that is the unique part of our project that helps any user to get blood donor information based on the pincode. User enters blood group and pincode then it displays the available information
•	Last page of user portal is ‘contact us’ page where the user can communicate their queries with the admins.the styling of pages is done using css and search parts are done by javascript.


•	Now we need to create a login page for admin panel this is done using js and php.
•	Admin page contains  dashboard, blood group,add donor,donor list,manage contact us query,Manage pages and update contact info
•	Dash board contains details about  blood groups and queries.
•	Blood group is where we edit blood groups incase if new blood group is discovered.
•	Add donor is similar to ‘become a donor’ page from user portal where admin can add donor details.
•	Manage contact us query  is where we can update details of ‘contact us’ page from user portal.
•	Manage pages is where we manage about and why become donor pages from userportal.
•	Update contact  is where we update the details of contact if necessary. Php and html is used for creation of pages css and js are used for styling pages.


8. UNIQUE PART OF THIS PROJECT:

	Uniqueness of our project is that, here a general user can  access the
Website and check the list of donors in nearby his place by just using
“pin code”  of the place and the “blood group” which he require.
	Before the start of this project we have visited a blood bank in our locality and asked about how they manage the record, and they just will maintain the amount of the blood present for each group and that can only be accessed by the staff. So we decided to develop a user friendly website.
	So we have created a website were both users and admin can access and search for donors.
	The user website has an option “search for blood donor”, here a user can search for a blood donor by just using the required blood group and the pin code of the locality in which the user id there. This displays out the information of all the donors listed in their locality.
	This project can help the people who are in an emergency requirement. This can save the life of a man.



9. PROCEDURE TO RUN THE PROJECT:

•	We need to install XAMPP software to connect the system to webpage. 
•	After that open XAMPP and start APACHE and MYSQL.
•	Extract the contents of bbms zip file to c:/xampp/HTDocs
•	Open browser and type localhost/phpmyadmin.
•	There you need to create a new database on left side. Name your database as 'bbms' and import the database from sqlfile/bbms.sql present in the extracted bbms folder.

BBMS has 2 parts:

1. User portal

After following the above steps type localhost/bbms in your browser and the user portal will open. Anyone can access user portal.

2. Admin portal

To access admin portal type localhost/bbms/admin in your browser

Username: admin	
Password: Test@12345 (password is case-sensitive).

You can run admin portal now and access various parts of the admin system.

10. SCREENSHOTS:
![image](https://user-images.githubusercontent.com/66869358/173081817-05f0f464-7f4e-4977-aa02-67aa8e503f6c.png)
![image](https://user-images.githubusercontent.com/66869358/173081861-f8481eed-0867-4463-b4c9-8a662a83416c.png)
![image](https://user-images.githubusercontent.com/66869358/173081879-873a410d-7d8f-4cbb-872e-36bc88f41933.png)
![image](https://user-images.githubusercontent.com/66869358/173081906-79a34528-f047-4f2e-8ef1-d194becc838e.png)
![image](https://user-images.githubusercontent.com/66869358/173081930-a6c95ff7-37eb-4b38-84c6-2f80486d4299.png)
![image](https://user-images.githubusercontent.com/66869358/173081982-e8b9c069-14db-41a2-8202-27ffb9438a9a.png)
![image](https://user-images.githubusercontent.com/66869358/173081997-fc54d8bd-f6ca-435c-a30f-57fb3d69051b.png)
