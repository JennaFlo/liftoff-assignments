# Project Outline
For this assignment, you will submit a high-level outline of your project. This can, and likely will, change over time. In particular, your mentor will provide feedback and direction and feedback to help sharpen your ideas. So don't worry if you feel unsure about some aspects of the outline, or if you have to change some things later.

## Assignment Description
[Project Outline Assignment](https://education.launchcode.org/liftoff/assignments/project-outline/)

## Submission Instructions

### Overview


  With this assignment I want to create an ordering interface for a food truck company. I want the customers to log in using a username that is a valid email address, and access the seasonal food truck menu. The menu items will be proceeded by check boxes where the orderer will be able to place an order from any of the three menus. The order will be contained in a SQL database and will be saved for future access.
  For new users, they will create a login so the structure from User-SignUp will be used, with [Required] fields and error messages nested into the html code. Onece the username is created, the info will be stored in a database. Users can then place orders and come back in the future and polace other orders using the same login. This can also be a feature to use for preordering and bulk ordering the day before, or if the user wants to use a catering feature for large-scale orders.
   Menus will be stored in databases and items can be added and removed from the Admin login. There will be a single controller for the Menus with Three Views: Summer, Winter, Pies. The theme of the foodtruck with be "Late Night Snacks" with menu items making up a range of quick, short-order cook style with things like, grilled cheese, nachos, mini pizzas, hotdogs, etc. The logos and the website will reflect the design of the foodtruck, with pictures of the food offered in the menu consistant with the images on the website and the truck design.


### Features
 Menu: We will cretae apage that displays the food offered on the truck. It will be a menu that has check boxes before each item; the     check boxes will concantinate a ongoing list that will complile the order in a seperate database. The order will then be stored and     sent to the team in the truck and through SMS to the customer.The menu will be changed by the Admin login and will be able to change 
  by that user based on available items. A "sold out" label may be added to enable the Admin to let customers know if that item is 
  orderable on the truck that day

MAP: A map will be added using the google map locator that will allow for customers to locate the truck when it is moving. There could
  be a set route for the truck, or we could use it as a feature that can be updated by the Admin on the page- more clarification for    
  this feature will be added as the project develops
  
SMS: We want to access the ability for order and communication with the customer baout ordered items, pricing, and potentially locations    of the foodtruck is that changes. Our plan is to use Trillio to create the communication between the customer and the site

Calendar: The Calendar will be a statically coded item that will give a month long list of the events and locations of the foodtruck.
  It can include links to the locations and the events(i.e. concerts, festivals, locations of events) that will allow for the customers   to access the food truck outside of the regular schedule. 
 


### Technologies
C#:  build with ASP.NET MVC, with Microsoft Entity Framework
SQL: method to save orders. user signup
CSS/HTML: form layouts
Bootstrap: addded HTML/ CSS Structure


### What I'll Have to Learn

Bootstrap: Modifiying it from its standard format in teh ASP.NET 
Using data from a public API; goggle Maps
Sending an order to an email(maybe printing a ticket)- process like on Square with a Point of Sale option. not sure how to do that yet 
Upload images of food by customers for the review portion of the page
