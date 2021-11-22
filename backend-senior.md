# Test task for senior backend developer position

### This test will be based on the some of the platforms we work with. The candidate will create a Django  project that:

1. Creates Users and save them in a local PostreSQL database

2. Integrates with our Chargeebee Test Environment via Django Async calls to
   - create customer
   - create subscription
3. Create Chargebee Webhook
4. Process data from the callback
   - Create use of data from this callback earns the candidate extra marks    
6. Implements an authentication layer that:
   - uses emails and passwords 
   - has forgot password option 
   - returns an auth token on successful login
7. Generates random internation call logs for 20 customers and generates weekly reports for customers 
    - call rates are region based.(a csv file must be provided)

The project will be deployed on *Digital Ocean*

### The goal is to test the candidates' ability to:

1. Work with 3rd party APIs
2. Secure intergrations 
3. Queue log running tasks 
4. Cache operation results
5. Generate reports 
6. Work with Django's internal authentication&authorization module
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
