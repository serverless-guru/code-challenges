# AWS API Gateway CRUD REST API

## The Challenge

Build a REST API with AWS API Gateway that supports CRUD functionality (Create, Read, Update, Delete). Don't use service proxy integration directly to DynamoDB from API Gateway.

Please use GitHub Actions, AWS CodePipeline, or the CI/CD tooling for your chosen framework to handle deployments.

You can take screenshots of the CI/CD setup and include them in the README.

The CI/CD should trigger a deployment based on a git push to the repository's default branch, for example `main`, and deploy the backend REST API and any other resources, such as DynamoDB tables.

### Requirements

1. All application code must be written using Node.js. TypeScript is encouraged, and JavaScript is acceptable

2. All AWS infrastructure must be automated with IaC using [Serverless Framework](https://www.serverless.com), [AWS CDK](https://docs.aws.amazon.com/cdk/v2/guide/home.html), or CloudFormation as needed

3. The API Gateway REST API should store data in DynamoDB

4. There should be 4-5 Lambda functions that include the following CRUD functionality (Create, Read, Update, Delete). Don't use service proxy integration directly to DynamoDB from API Gateway

5. Build the CI/CD pipeline to support multi-stage deployments, such as dev and prod

6. The template should be fully working and documented

7. A public GitHub repository must be shared with frequent commits

8. A video should be recorded (www.loom.com) of you talking over the application code, IaC, and any additional areas you want to highlight in your solution to demonstrate additional skills

Please spend only what you consider a reasonable amount of time for this.

## Optionally

Please feel free to include any of the following to show additional experience:

1. Make the project fit a specific business case e.g. Coffee Shop APIs vs Notes CRUD directly from AWS docs
2. AWS Lambda packaging
3. Organization of YAML files
4. Scripts or package manager commands to support deployment
5. Unit tests, integration tests, contract tests, etc
6. CI/CD authentication using short-lived credentials, such as GitHub Actions OIDC, instead of long-lived AWS access keys
