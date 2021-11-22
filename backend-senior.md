# Test task for senior backend developer position

----

### This test will be based on some of the platforms we work with. You will create a Django project with the requirements listed below:

1. Create Users and save them in a local PostgreSQL database
2. Integrate project with our Chargebee Test Environment via Django Async calls to
   - create customer
   - create subscription
3. Create Chargebee Webhook
4. Process data from the callback
   - Create use of data from this callback *(earns you extra marks)*
5. Implement an authentication layer that:
   - uses emails and passwords 
   - has `forgot password` option 
   - returns an auth token on successful login
6. Generate random international call logs for 20 customers and generate weekly reports for customers 
    - call rates are region based _(we will provide you with a CSV file)_

Deploy the project on **Digital Ocean**.

### The goal is to test candidate's ability to:

1. Work with 3rd party APIs
2. Secure intergrations 
3. Queue log running tasks 
4. Cache operation results
5. Generate reports 
6. Work with Django's internal authentication & authorization module
7. Work with Django Async 
8. Schedule tasks
9. Work with large data sets
10. Deploy Django applications
11. Learn and use new tools quickly 


### Tools and platforms 

1. Python 3.10.0 
2. Django 3.2.9
3. PostgreSQL 9.6
4. Chargebee
5. Digital Ocean 
