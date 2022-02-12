# Role_Hierarchy
Zoho level 1 Assignment

Steps to run (linux env):

Go to the downloaded directory where the file Role_Hierarchy.cpp is present , Open terminal in that directory type and enter the following
g++ Role_Hierarchy.cpp
./a.out 


OR 
execute directly here https://onlinegdb.com/IID_qNSRr

Features:
    1. Create the root role and display it.
    2. add sub role operation to the root role.
    3. display the roles in role hierarchy order.
    4. Support delete role operation, transfer children to the role entered by the user as input.
       (If the role to be transferred is the child role of the deleted role, then also the
        parent of deleted role becomes the parent of the role to be transferred.)
    5. Users can be added and a role can be assigned to them. Same role can be assigned to
       more than one user but an user can have only single role.
    6. Display each user with the list of users who are working under the particular user.
    7. Support delete user operation, 
    8. find the number of users between the top most role user and the entered user.
    9. find the height of the entire role hierarchy.
    10. find the top most common boss of the entered users.

-----------------
Assumptions:
    1. All inputs are valid
    2. No two user have the same name 
