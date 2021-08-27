SQL TEST
=======
[Have a nice working day](https://www.youtube.com/watch?v=_nrm_vei5TE).

Resources:
-----------
* database.sql: Data
* passwords.csv: new password 
* answer1.sql: DoSth...with question 1 
* answer2.sql: DoSth...with question 2
* answer3.php: DoSth...with question 3

Requirement :
-----------
**Question 1:**. 
- We have 5 types of coupons and the parent passwords are associated with the coupon via the password_coupon table. Please write your SQL code at answer1.sql to calculate the total number of parent password associated with each coupon type

Example: 


id | name | count_parent_password 
--- | --- | ---
cafcdfa4-4e22-480e-9d4f-9a0f68da0ab0 | Buy One Get One | 56 
cafcdfa4-4e22-480e-9d4f-9a0f68da0ab1 | 50% OFF | 56 
.....


**Question 2:**.
- Please write your SQL code at answer2.sql to find the parent passwords with the total number of child passwords greater than 20 and order it by desc

Example: 


id | count_child
--- | ---
cafcdfa4-4e22-480e-9d4f-9a0f68da0ab0 | 70
cafcdfa4-4e22-480e-9d4f-9a0f68da0ab1 | 66
cafcdfa4-4e22-480e-9d4f-9a0f68da0ab2 | 40
.....

**Question 3:**.
- With reading file function at PHP test. Please write your PHP code at answer3.php to read file passwords.csv and save it into the passwords table. Attention to use transaction,  array_chunk. 

Keep your mind on the convention.
Good Luck! 

