# aws-lambda-starter

A Very basic lambda function to explore AWS Lambda Service

## Steps to create .zip to upload as AWS Lambda Function

-   Install Dependencies by running
    `npm install`
-   Once the dependencies are installed, you can build a .zip package that can be deployed to AWS Lambda:
    `npm run package`
    This should create a file called http-metrics.zip.
-   You would also need to set correct IAM permissions for a Lambda function to send metrics to AWS CloudWatch. You can copy an IAM policy from the iam-policy.json file in this project.
