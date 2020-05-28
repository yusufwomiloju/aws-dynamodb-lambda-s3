# aws-dynamodb-lambda-s3
Changes in DynamoDB triggers a lambda function to write changes to a S3 bucket.

## Architecture Overview
![Architecture Diagram](/images/aws-dynamodb-lambda-s3.png)

Inserting records into the DynamoDB table triggers the invocation of a Lambda function. The newly added records are then saved to a .json file which is placed in an S3 bucket. 