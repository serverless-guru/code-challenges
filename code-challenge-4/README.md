# AWS AppSync API Development v2

## The Challenge

Build an AWS AppSync API that supports CRUD functionality (Create, Read, Update, Delete). Don't use mapping templates directly to DynamoDB from AppSync. Use GitHub Actions, AWS CodePipeline, or the CI/CD tooling for your chosen framework.

You can take screenshots of the CI/CD setup and include them in the README.

The CI/CD should trigger a deployment based on a git push to the repository's default branch, for example `main`, and deploy the backend API.

### Requirements

1. All AWS infrastructure must be automated with IaC using Serverless Framework, AWS CDK, or CloudFormation as needed

2. The AppSync API should store data in DynamoDB

3. There should be 4-5 Lambda functions that include the following CRUD functionality (Create, Read, Update, Delete). Don't use mapping templates directly to DynamoDB from AppSync

4. Build the CI/CD pipeline to support multi-stage deployments

5. The template should be fully working and documented

6. A public GitHub repository must be shared with frequent commits

7. A video should be recorded (www.loom.com) of you talking over the application code, IaC, and any additional areas you want to highlight in your solution to demonstrate additional skills

Please spend only what you consider a reasonable amount of time for this.

## Optionally

Create a frontend with React and a modern UI library such as MUI, Tailwind CSS, Chakra UI, or shadcn/ui. The frontend can use Amplify or the AWS SDK to connect to your AppSync API for CRUD functionality.
