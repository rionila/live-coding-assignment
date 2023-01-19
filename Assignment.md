Assignment:

1. Create object models per the db schema provided (assignment_db)
2. Create endpoints to Get All Orders, Create Order, Update Order, Get All Orders Created After Date
3. Create endpoints to Get All Users, Create User, Delete User
4. Create endpoint to get All Orders for a User.
5. Using SecurityFilterChain, make it so that in order to call any endpoint the user must have the predefined role: "default", except for the paths provided in the OPEN_URLS array.
6. Make it so that in order to call the Create User and Delete User endpoint, the user must have the predefined role: "admin".


Bonus:
1. Vending machine problem: 
* Let there be a vending machine that only accepts 10 EUR bills. 
* The input is an array of all the prices of the products selected by the user, ex: [2.5, 7, 4.1]
* The vending machine can only give back change in 10 cent and 50 cent coins.
* Write one function which calculates and returns in an array: the number of bills the user has to introduce, the number of 50 cents coins and the number of 10 cents coins, considering that the machine has to return the minimum number of coins possible.
