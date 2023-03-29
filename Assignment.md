# Assignment:

1. Create entities per the db schema provided (assignment_db) considering that a User can have multiple Orders;
2. Create endpoints to Update Order, Get All Orders Created After Date;
3. Create endpoints to Create a User;
4. Create endpoint to get All Orders for a User; (overwrite the Jpa method with a native query && return all orders without the "client" property without creating a separate DTO); 
5. Create endpoint that returns the users in the database that are from the same city as any user returned by calling a 3rd party service to get other "external" users (URL - https://dummyjson.com/docs/users);
6. Create a front-end project (Angular/React) in which to have a page with a date input to send to the back-end in order to get the list of orders after that date and display in a table;
7. Create routes to another component. Restrict access to this component if you do not have the predefined role "admin";
8. Update Security configuration so that in order to call any endpoint the user must have the predefined role: "default", except for the paths provided in the OPEN_URLS array;
9. Make it so that in order to call the Create User and Delete User endpoint, the user must have the predefined role: "admin";
