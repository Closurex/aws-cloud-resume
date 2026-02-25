AWS Cloud Resume 

This project implements a serverless resume website architecture on Amazon Web Services.

The frontend is a static website hosted in Amazon S3 and distributed globally via Amazon CloudFront. A visitor counter is implemented using a serverless backend consisting of AWS Lambda and Amazon DynamoDB. The Lambda function performs an atomic update operation on DynamoDB to increment and return the current view count.

Key components:

Amazon S3 – Static website hosting

Amazon CloudFront – CDN distribution and HTTPS delivery

AWS Lambda – Serverless compute for the API

Amazon DynamoDB – Persistent storage for the visitor counter

IAM – Least-privilege access control

Git & GitHub – Source control

CI/CD pipeline for automated deployments
