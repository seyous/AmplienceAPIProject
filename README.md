# AmplienceAPIProject

# Amplience Technical Test


### The Test

I generated a key value for the clientid and the client secret for the endpoint.
OAuth2, uses the client secret mechanism as a means of authorizing a client, the software requesting an access token. 
Users are authenticated (proven that they are whom they say they are), while apps are authorized.

I use postman as a tool to validate the json following json data data return from the endpoint
name = Gregory Loscombe
- id = 15330
- company = Amplience
- location = Manchester
- public repos = 5
- public gists = 11
- followers = 13
- following = 28
 

### Languages
javascript, 

Test Result
The result of API request is in a collection called AmplienceAPIUsers and the collection montior is used to run test according to schedule
The result of test is in the AmplienceAPIUsers.postman_test_run.json file
you can the test in postman using the link sent to your email.


### Part 2
The framework was developed using selenium, speckflow, Restsharp, Nunit and C# language
The folders includes, features, Hooks step, pageobj

features - stores information on the scenarios and 
the feature file scenario get an API response from the endpoint and assert if the response json format is true.
the pageobj contains the pageobject class called RestAPIAelper containa the methods and function perform on the endpoint
Step file contain each step definition for every scenario in the feature file

### Test Result
The test will Validate the HTML presentation layer (https://github.com/mojombo) is correctly displaying the information returned from the api
This test  allow re-pointing to any user, and read the data from the API
to determine that the frontend should render
