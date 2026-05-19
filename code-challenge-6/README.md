# Full-Stack REST API Application on AWS

## The Challenge

### First Part: Serverless Backend

Build a REST API with AWS API Gateway that supports CRUD functionality (Create, Read, Update, Delete). Don't use service proxy integration directly to DynamoDB from API Gateway.

Please use GitHub Actions, AWS CodePipeline, or the CI/CD tooling for your chosen framework to handle deployments.

You can take screenshots of the CI/CD setup and include them in the README.

The CI/CD should trigger a deployment based on a git push to the repository's default branch, for example `main`, and deploy the backend REST API and any other resources, such as DynamoDB tables.

### Second Part: React Frontend

Build a frontend application in React that connects to the serverless backend application. The React application must use all 4 CRUD functionality.

The frontend should be visually appealing and use modern web design. Please use a widely practiced CSS or component library instead of custom CSS only.

Application must follow responsive web design for at least 4 different device sizes.

Deployment of the React application is up to your choice. Please provide your entry point URL of the React application when finished.

### Requirements

1. All application code must be written using JavaScript or TypeScript. The backend application must be written in Node.js and the frontend application must be written in React

2. Backend AWS infrastructure must be automated with IaC using [Serverless Framework](https://www.serverless.com), [AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/home.html), or CloudFormation as needed

3. The API Gateway REST API should store data in DynamoDB

4. There should be 4-5 Lambda functions that include the following CRUD functionality (Create, Read, Update, Delete). Don't use service proxy integration directly to DynamoDB from API Gateway

5. Build the CI/CD pipeline to support multi-stage deployments, such as dev and prod

6. The template should be fully working and documented

7. A public GitHub repository must be shared with frequent commits

8. A video should be recorded (www.loom.com) of you talking over the application code, IaC, and any additional areas you want to highlight in your solution to demonstrate additional skills

Please spend only what you consider a reasonable amount of time for this.

## Optionally

Please feel free to include any of the following to show additional experience:

1. Make the project fit a specific business case, instead of a skeleton CRUD request/response.

2. AWS Lambda packaging

3. Organization of YAML files

4. Scripts or package manager commands to support deployment

5. Unit tests, integration tests, load testing, etc

6. Setup AWS Cognito as part of the backend task and use it for app signup/login. All pages accessible only to authorized users except signup/login

7. CI/CD authentication using short-lived credentials, such as GitHub Actions OIDC, instead of long-lived AWS access keys
