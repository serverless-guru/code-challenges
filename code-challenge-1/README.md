# AWS AppSync API Development

## The Challenge

Build an AWS AppSync API that supports CRUD functionality (Create, Read, Update, Delete) and has CI/CD configured.

You can take screenshots of the CI/CD setup and include them in the README.

The CI/CD should trigger a deployment based on a git push to the repository's default branch, for example `main`, and deploy the backend API.

### Requirements

1. All AWS infrastructure must be automated with IaC using Serverless Framework, AWS CDK, or CloudFormation as needed

2. The AppSync API should store data in DynamoDB

3. GitHub Actions, AWS CodePipeline, or the CI/CD tooling for your chosen framework should be used to support multi-stage deployments

4. The template should be fully working and documented

5. A public GitHub repository must be shared with frequent commits

6. A video should be recorded (www.loom.com) of you talking over the application code, IaC, and any additional areas you want to highlight in your solution to demonstrate additional skills

Please spend only what you consider a reasonable amount of time for this.

## Optionally

Create a frontend with React and a modern UI library such as MUI, Tailwind CSS, Chakra UI, or shadcn/ui. The frontend can use Amplify or the AWS SDK to connect to your AppSync API for CRUD functionality.
