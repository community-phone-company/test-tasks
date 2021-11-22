# Test task for backend developer position

----

### This test will be based on some of the platforms we work with. You will create a Django project with the requirements listed below:

1. Create Users and save them in a PostgreSQL database
2. Implement an authentication layer that:
   - uses emails and passwords. **The password MUST be generated on server side and email the user via a background task**.
   - has `forgot password` option 
   - returns an auth token on successful login
   
3. Generate random call logs for 5 customers and generate weekly reports for customers 
    - call rates are region based _(we will provide you with a CSV file)_

Deploy the project on **Digital Ocean**.

### The goal is to test candidate's ability to:

1. Queue log running tasks 
2. Cache operation results
3. Generate reports 
4. Work with Django's internal authentication & authorization module
5. Work with Django Async 
6. Schedule tasks
8. Deploy Django applications
9. Work with files 


### Tools and platforms 

1. Python 3.10.0 
2. Django 3.2.9
3. PostgreSQL 9.6
4. Chargebee
5. Digital Ocean 
