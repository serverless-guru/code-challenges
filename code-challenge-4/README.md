# AWS AppSync API Development v2

## The Challenge

Build a Serverless Framework API with AWS AppSync which supports CRUD functionality (Create, Read, Update, Delete) *don't use mapping templates directly to DynamoDB from AppSync and use GitHub Actions CI/CD pipeline, AWS CodePipeline, or Serverless Pro CI/CD.

You can take screenshots of the CI/CD setup and include them in the README.

The CI/CD should trigger a deployment based on a git push to the master branch which goes through and deploys the backend Serverless Framework API.

### Requirements

1. All AWS Infrastructure needs to be automated with IAC using Serverless Framework and CloudFormation as needed

2. The AppSync API should store data in DynamoDB

3. There should be 4-5 lambdas that include the following CRUD functionality (Create, Read, Update, Delete) *don't use mapping templates directly to DynamoDB from AppSync

3. Build the CI/CD pipeline to support multi-stage deployments

4. The template should be fully working and documented

4. A public GitHub repository must be shared with frequent commits

5. A video should be recorded (www.loom.com) of you talking over the application code, IAC, and any additional areas you want to highlight in your solution to demonstrate additional skills

Please spend only what you consider a reasonable amount of time for this.

## Optionally

Create a frontend with ReactJS and Material UI which uses the Amplify library to connect to your AppSync API for the CRUD functionality.
