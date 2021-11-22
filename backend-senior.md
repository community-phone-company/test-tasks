# Test task for senior backend developer position

This test will be based on the some of the platforms we work with. The candidate will create a Django  project that:

1. Integrates with our Chargeebee Test Environment 
   - create customer
   - create subscription 
   - create webhooks
   - process data from the callbacks
2. Implements an authentication layer that:
   - uses emails and passwords 
   - has forgot password option 
   - returns an auth token on successful login
3. Generates random internation call logs for 20 customers and generates weekly reports for customers 
    - call rates are region based.(a csv file must be provided)


The goal is to test the candidates' ability to:

1. Work with 3rd party APIs
2. Secure intergrations 
3. Queue log running tasks 
4. Cache operation results
5. Generate reports 
6. Work with Django's internal authentication&authorization module
7. Schedule tasks
8. Work with large data sets 
