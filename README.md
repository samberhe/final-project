# final-project
REST/SOAP API Integration project

Mule ESB Final Project Requirement

Below are the functionality you will deliver:-
 Use file End-Point to save the REST data.
 Use scatter gathering for redundant configurations.
 Create error handling strategy for all errors.
 Use MUNIT in order to test the flow.
 Use GIT to version control and collaboration
Use the following REST application for your information
and comparison.

1. To get all employees
Request type: GET
Endpoint: http://35.245.153.252/procdi/api/read.php

2. To get a single employee
Request type: GET
Endpoint:
http://35.245.153.252/procdi/api/single_read.php?id=2

3. To add new employee
Request type: POST
Endpoint: http://35.245.153.252/procdi/api/create.php
Sample body:
{
"name": "Andrew Best",
"email": "jeramie_roh@hotmail.com",
"age": "51",
"designation": "Geneticist",
"created": "2019-01-02 02:20:30"
}

4. To update existing employee
Request type: PUT
Endpoint: http://35.245.153.252/procdi/api/update.php

Sample body:
{
"id": 9,
"name": "Andrew Best",
"email": "jeramie_roh@hotmail.com",
"age": "51",
"designation": "Geneticist",
"created": "2019-01-02 02:20:30"
}

5. To delete an employee
Request type: DELETE
Endpoint: http://35.245.153.252/procdi/api/delete.php
{"
id" : 26
}
