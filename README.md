1- Unzip the desafio-cypress-qa.zip file 
2- Open Visual Studio Code directly from the folder (it will load the automation files)
3- Make sure Node.js is installed (at least version 20.19); if not, install it 
4- Open the VS Code terminal and install the Cypress dependencies (npm install cypress@14.1.0 -D) — version 14.1.0 is recommended 5- To run the tests, open Cypress (npx cypress open) and run E2E Testing (Specs / Login)

List of automated scenarios

Inside the Login.cy file there are 3 login test scenarios with 1 test case each. I chose the login feature because it’s more repetitive from a user perspective and essential to the functioning of any application.

1- Successful user login (validates that the user can log in correctly)
2- Error — invalid user (does not log in as expected, validating the alert message for incorrect email) 
3- Error — invalid password (does not log in, validating the alert message for incorrect password)
