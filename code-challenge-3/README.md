# Track Clicks on Website

## The Challenge

Build a link tracking backend API which does the following:

1. When a user clicks a link it should trigger an HTTPS request to an API Gateway or AppSync endpoint

2. Behind the API Gateway or AppSync endpoint should be a Lambda function to process the event

3. The Lambda function should record this event into a database like AWS DynamoDB

4. The Lambda should then return a JSON response after saving the event in the database

### Requirements

1. All AWS Infrastructure needs to be automated with IAC using Serverless Framework and CloudFormation as needed

2. A public GitHub repository must be shared with frequent commits

3. A video should be recorded (www.loom.com) of you talking over the application code, IAC, and any additional areas you want to highlight in your solution to demonstrate additional skills

Please spend only what you consider a reasonable amount of time for this.

## Optionally

Create a frontend with ReactJS or Vue.js which will make the HTTPS request to the API Gateway or AppSync endpoint.

Automate the creation of the frontend with your preferred tooling.