# users_collection_postman_collection

* Import "users_collection.postman_collection.json" into your workspace.
* * The Collection Has 2 Requests
** The First Request is "Get_All_Users" that uses Get method to get the response that has list of data of all users in page (2).
**** There is code script in Test section of this request that checks the status code and validate the count of users retrieved in this response and a program to assign the a random user's data to collection variable.
***** The Second Request is "Single_User" that uses Get method to get response of certain user data using user id as request parameter.
****** there is a code script in Test section of this script that test the status code and make comparison withe rhe retrieved response data of this user in this request with the same user date from the "Get_All_Users" requset.
