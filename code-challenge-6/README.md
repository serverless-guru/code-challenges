  

# Full-Stack REST API Application on AWS

## The Challenge

  

### First Part: Serverless Backend

Build a Serverless Framework REST API with AWS API Gateway which supports CRUD functionality (Create, Read, Update, Delete) *don't use service proxy integration directly to DynamoDB from API Gateway

  

Please use GitHub Actions CI/CD pipeline, AWS CodePipeline, or Serverless Pro CI/CD to handle deployments.

  

You can take screenshots of the CI/CD setup and include them in the README.

  

The CI/CD should trigger a deployment based on a git push to the master branch which goes through and deploys the backend Serverless Framework REST API and any other resources e.g. DynamoDB Table(s).

  

### Second Part: React Frontend

Build a frontend application in React that connects to the serverless backend application. The React application must use all 4 CRUD functionality.

  

The frontend should be visually appealing and utilizes modern web design. Please use widely practiced CSS library instead of using your own custom CSS

  

Application must follow responsive web design for at least 4 different device sizes.

  

Deployment of the React application is up to your choice. Please provide your entry point url of the react application when finished.

  

### Requirements

0. All application code must be written using Javascript. Typescript is acceptable as well. Backend application is written in Node.js and frontend application written in React

  

1. Backend AWS Infrastructure needs to be automated with IAC using [Serverless Framework](https://www.serverless.com)

  

2. The API Gateway REST API should store data in DynamoDB

  

3. There should be 4-5 lambdas that include the following CRUD functionality (Create, Read, Update, Delete) *don't use service proxy integration directly to DynamoDB from API Gateway

  

4. Build the CI/CD pipeline to support multi-stage deployments e.g. dev, prod

  

5. The template should be fully working and documented

  

6. A public GitHub repository must be shared with frequent commits

  

7. A video should be recorded (www.loom.com) of you talking over the application code, IAC, and any additional areas you want to highlight in your solution to demonstrate additional skills

  

Please spend only what you consider a reasonable amount of time for this.

  

## Optionally

  

Please feel free to include any of the following to show additional experience:

  

1. Make the project fit a specific business case, instead of a skeleton CRUD request/response.

2. AWS Lambda packaging

3. Organization of YAML files

4. Bash/other scripts to support deployment

5. Unit tests, integration tests, load testing, etc

6. Setup AWS Cognito as part of the backend task and use it for app signup/login. All pages accessible only to authorized users except signup/login
