CustomerOrderMgmt-App-FEND

6 Steps to Completing API:

1. Planning

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

2. Set Up and Backend
3. Testing
4. Frontend and Testing
5. Finish Up and ReadMe.Md
   Challenges:  
   Upon close review of requirements, only two models are needed, not three. Therefore, updated ERD and refactored customer model to customer_orders        model.
   Debug "Failure to Start" error.
   Uncertain if product model should include fields "Quantity" and "Total Price" or if SQL quiry generates them and adds count and total to forms. Since    these elements can be added to form through calculation, they are not being added to ERD.
   Uncertain about decimal data structure for total price and product price; note:  in IntelliJ, use Float as the data structure 
6 Presentation
