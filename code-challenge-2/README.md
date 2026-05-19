# AWS SAM Migration

## The Challenge

Take an AWS SAM template and migrate it to Serverless Framework or AWS CDK.

### Requirements

1. The AWS SAM template should be converted to Serverless Framework or AWS CDK

2. AWS SAM-specific properties that the chosen framework does not support should be removed or replaced

3. All properties such as AWS Lambda memory size should be modified to use the proper casing and location

4. The converted template should be able to be deployed and support multi-stage deployments

5. A public GitHub repository must be shared with frequent commits

6. A video should be recorded (www.loom.com) of you talking over the application code, IaC, and any additional areas you want to highlight in your solution to demonstrate additional skills

Please spend only what you consider a reasonable amount of time for this.

Take this AWS SAM template and turn it into Serverless Framework or AWS CDK. High level instructions below.

## More Information

* [Result](#result)

* [Goal](#goal)

* [Bonus](#bonus)

## Result

* API Gateway + Lambda function isolated

* VPC isolated

* Database isolated

* (optional) Permissions isolated

* Everything deploys properly

## Goal

1. Convert this AWS SAM template to Serverless Framework or AWS CDK

2. Remove all unnecessary resources that the chosen framework creates automatically

3. Replace intrinsic functions with the chosen framework's equivalent syntax or construct patterns

4. Update all AWS resource names to be dynamic by stage

5. Update all hardcoded region/stage values to be dynamic

6. Split the resources into separate files or stacks based on logical groupings and isolation of resources

7. Add X-Ray tracing, API Gateway REST API logging, and Lambda packaging or bundling so only required application files are deployed

8. Add dynamic stage/region configuration

9. Send over to Serverless Guru for review

## Bonus

1. Add framework outputs so isolated services or stacks can communicate together

2. Set up CI/CD deployments using an AWS IAM role instead of a local profile

3. Move the clientId and clientSecret to a secure parameter store or secrets manager for dev and prod
