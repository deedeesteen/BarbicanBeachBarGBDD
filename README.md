# BarbicanBeachBarGBDD
Object-Oriented Programming Final Group Project
Barbican Beach Bar is new restaurant that was established in the parish of Kingston. To compete with nearby restaurant, the owner would like an automated system that displays a menu and show prices for the items available. This system will create a more reliable, tech-savvy and user friendly customer service that will enhance the customer experience.

There are two types of users, these are Admin and Customer. Users have a user name and password. The system should allow the user to login using the following credentials. You are not required to create/register new users.

Admin
- Username = admin
- Password = admin

Customer
- Username = cust1
- Password = qwerty

Admin users should have the following functionality:
- Add new items to menu
- Edit menu items
- Delete menu items
- Search for menu items

Customer users should have the following functionality:
- View All Items (Menu)
- Search for Items
- View Orders

* View All Items (Menu)
The menu will show the list of items with their respective price and preparation time. For each item, the system keeps tracks of the item id (auto), name, price, preparation time and quantity. The prepration time is stored in minutes, the quantity allows the user to select multiple items of the same type. The customer must be able to select multiple items from the menu. Once an item is selcted the quanitity should be specified.

* Search for Items
Customers should be able to search for items using the name. Allow the customer to perform multiple searches and item selection.

* View Orders
The order screen should show a list of all the orders with the order id (auto), total cost and total preparation time. Orders should be stored to a text file. Customers should also be able to cancel (delete) orders.

Required:
Perform an object-oriented analysis on the proposed system described above, and then design the system using the unified modelling language (UML). Utilize composition and inheritance in your design to increase reusability and reduce system complexity.

Grading Scheme (100 marks): General Mark Breakdown
* Documentation (20 marks)
  o Group Report (outlining contribution(s) of each member) [3 marks]
  o Object-Oriented Analysis and Design of system [12 marks]
  o User Manual [5 marks]
  
* Source Code (30 marks)
  o Comments [3 marks]
    - Each file should have details for the student(s) who wrote the file
    - Practice use of self-commenting files (i.e. proper variable and method naming)
    - Proper use of inline and method comments where necessary
  o Naming Convention [2 marks]
    - Pascal Case should be used for naming classes
    - Camel Case should be used for variable and method naming
    - Ensure class files are named appropriately
  o Object-Oriented Programming Techniques [20 marks]
    - Inheritance, Polymorphism, Composition
    - Method overriding and overloading
  o Use of Files [5 marks]
    - Proper implementation of appropriate file management
    - Functionality (50 marks)
  o Robustness [10 marks]
    - User Input validation
    - Error / Exception Handling
    - Program Navigation (i.e. Menu System)
  o User Interface
    - Ease of User Interaction [6 marks]
    - Appropriate Notifications (i.e. error and information messages) [4 marks]
  o System Functionality Implemented
    - Customer
    - View All Items [10 marks]
    - Search Items [5 marks]
    - View Orders [7 marks]
    - Admin
    - Add Item [2 marks]
    - Edit Item [2 marks]
    - Delete Item [2 marks]
    - Search Items [2 marks]
 
Extra Marks (20 marks):
A project that satisfies the program's functional requirements can gain additional 20 marks:
* + 10 marks – Awarded for use of colour and graphics to enhance the look and feel of the
Program.
* + 10 marks – Show a countdown of the meal preparation time in the view orders screen.
