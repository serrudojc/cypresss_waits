# cypresss_waits

Required Practice

Start by reading the following document about waits in cypress: https://docs.cypress.io/api/commands/wait 

In this practice we are going to implement waiting strategies to simulate the processing of an AJAX request to a web server. We need to create tests that should be able to wait for an element to show up.

The site to test is the following: http://uitestingplayground.com/ajax. There we will find a button that, when pressed, will simulate the launch of a request. Once the button is clicked, there will be a waiting time to obtain a response message. The defined test cases should validate that the message is displayed using waiting strategies with Cypress. 

Make sure to create at least 3 scenarios, every one of them using a different waiting strategy to wait for the success message to show up. (Waiting strategies should be: waiting a specific time, waiting with a BDD expectation, and waiting for the service to return a response).
