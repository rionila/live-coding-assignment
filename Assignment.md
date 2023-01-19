# Assignment:

1. Create entities per the db schema provided (assignment_db) considering that a User can have multiple Orders;
2. Create endpoints to Get All Orders, Create Order, Update Order, Get All Orders Created After Date;
3. Create endpoints to Get All Users, Create User, Delete User;
4. Create endpoint to get All Orders for a User;
5. Create a front-end project (Angular/React) in which to have a page with a date input to send to the back-end in order to get the list of orders after that date and display in a table;
6. Update Security configuration so that in order to call any endpoint the user must have the predefined role: "default", except for the paths provided in the OPEN_URLS array (hint: Using SecurityFilterChain Bean);
7. Make it so that in order to call the Create User and Delete User endpoint, the user must have the predefined role: "admin";




##Bonus:
### Vending machine solution: 
* Let there be a vending machine that only accepts 10 EUR bills;
* The input is an array of all the prices of the products selected by the user, ex: [2.5, 7, 4.1];
* The vending machine can only give back change in 10 cent and 50 cent coins;
* Write one function which calculates and returns in an array: the number of bills the user has to introduce, the number of 50 cents coins and the number of 10 cents coins, considering that the machine has to return the minimum number of coins possible;
