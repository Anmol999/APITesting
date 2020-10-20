1)For D API

# API_Projects
I have used Postman for this task. 
Different assertions are applied.
Corresponding Collections are created for Parameterization.
Reports are logged on to htmlExtra showing over all summary showing iterations, requests, test-scripts, assertions,total run duration, total data received, average response time and in case of any failure we get the details of failure.

Following command can be used directly to run the test through command line:
newman run APITesting.postman_collection.json -e ProductionEnv.postman_environment.json -n3  -r htmlextra
*** -n3 mean iterating the test 3 times, and can be changed according to requirement.



2) For Swagger API
# API_Projects
Postman is used. 
Different assertions are applied 
Corresponding Collections are created for Parameterization.
Reports are logged on to htmlExtra showing over all summary showing iterations, requests, test-scripts, assertions, 
total run duration, total data received, average response time and in case of any failure we get the details of failure.

Folloing command can be used to Run the it through command line:
newman run APITesting.postman_collection.json -e Swagger-Test.postman_environment -n3  -r htmlextra
*** -n3 mean iterating the test 3 times, and can be changed according to requirement.


3) For Soap UI Projects
# SoapUIProjects
Added the Concept of Groovy Script, 
Property Transfer, end to end testing, 
Generating CSV Report 
Assertions with Xquery Parameter. 
I have also included RestAPI's service with assertions using JSonPath

