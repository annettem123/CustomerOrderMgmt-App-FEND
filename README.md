CustomerOrderMgmt-App-FEND

Summary of 6 Steps to Completing API Project:

1.    Planning - Github

      1.1 Create 2 repos Name-App-FEND public with ReadMe.Md & Name-App-BEND;
      
      1.2 Create 1 Project for Project Mgmt Plan (ToDo,  Development, Testing, Done);
      
      1.3 ReadMe:  AppName, App Desc, ERD, User Stories, Wireframes, MVC Design.
      
2.   Set Up and Backend 

      2.1 PostgreSQL: Create new database and connect to it; 

      2.2 Terminal:  mkdir Name-App-FEND git clone; mkdir Name-App-BEND git clone;

      2.3 IntelliJ: Create New Project and configure same.  

3.   Testing 

      3.1 Postman: test endpoints;

      3.2 give mgr BEND & FEND completion status;

      3.3 do a mini presentation.

4.   Frontend and Testing

      4.1 Angular:  modules;

      4.2 JUnit.

5.   Finish Up & ReadMe 

      5.1 Finish all programming;

      5.2 Deploy to Heroic;

      5.3 ReadMe: add challenges & what else would be done if there was more time; 

      5.4 Practice presentation skills.

6.   Presentation 

      6.1 ReadMe:  add url to Readme;

      6.2 Present app demo. 




1.  Planning

   App Name:  CustomerOrderMgmt-App
   
   App Description:  This project involves using a REST API for a product database which allows for users to view information and create one product.
    
   [CustomerOrderMgmt-App-ERD.pdf](https://github.com/annettem123/CustomerOrderMgmt-App-FEND/files/8496850/CustomerOrderMgmt-App-ERD.pdf)

   CustomerOrderMgmt-App User Stories

Minimum Viable Product (MVP)

As a user, one would like to view one product so that user can get the  information the of one product effortlessly.

As a user, one would like to list all products so that user can retrieve the information effortlessly.

As a user, one would like to create one product so that user can add products with payload of a product effortlessly.

As a user, one would like to view one order that includes order ID, customer name,  data signed, and  total price of the order, and it also includes information of all  products in this order (the product id, product name, product price and quantity of this product) so that user can retrieve all the pertinent information effortlessly.

Silver: 

As a user, one would like to update product so that user can change the price of a product effortlessly.

As a user, one would like to delete order so that user can cancel order effortlessly.

Wireframes:  


Model View Controller System Design (MVC):

This project is being built using the MVC design, implementing a Model, View, and Controller class.  The main objective of this structure is “Separation of Concerns” allowing each layer of the application to communicate with other layers for data logic and data access and abstraction.  This project consists of:

2 Model Classes
4 different types of Forms for building and sending JSON body objects
1 Service Class for business logic
Controller has 5 endpoints

2. Set Up and Backend

   Create a new database called "customerorder"



3. Testing



4. Frontend and Testing




5. Finish Up and ReadMe.Md
   Challenges:  
   Upon close review of requirements, only two models are needed, not three. Therefore, updated ERD and refactored customer model to customer_orders        model.
   
   Debug "Failure to Start" error.
   
   Uncertain if product model should include fields "Quantity" and "Total Price" or if SQL quiry generates them and adds count and total to forms. Since    these elements can be added to form through calculation, they are not being added to ERD.
   
   Uncertain about decimal data structure for total price and product price; note:  in IntelliJ, use Float as the data structure.
   
   Trying to make sense of how to prioritize different steps when different examples do the steps differently.
   
   Trying to make sense of how to prioritize different steps when different examples do the steps differently.
   
   Uncertain how to complete 6 days of work into 1 hour.
   
   
6 Presentation
