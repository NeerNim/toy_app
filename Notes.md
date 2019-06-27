Toy model for users
 - id integer 
 - name string
 - email string

Connect each micropost with singe user id 

Toy model for microposts
- id integer
- content text
- user_id integer

User resource where user is an object that can be created, read, updated and deleted

Weaknesses of this Users resource
- No data validation => accepts data as blank names, invalid email 
- No autehntication => No login or out, no way to prevent any user to perform operation
- No test => only generated test that does not have data validation
- No style or layout

