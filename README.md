# aws-distributed-photo-app
A photo recognition app leveraging the power of AWS core services for NoSQL databases, VPCs, subnets, load balancers, servers and rekognition service for high availability & good performance. This app was built to aid my preparation for the AWS Certifications & to gain a holistic understanding of how AWS applications work on the Cloud. The architecture for the app is given below. 

This is a mimic of a production application hosted on the AWS Cloud.
AWS Services used:

- S3 for storage
- SQS for distributed queues
- Lambda for serverless functions(asynchronous tasks)
- Elastic Beanstalk for Deployment
- Cognito for authentication & user pools
- rekognition for image recognition
- SNS for notification service
- DynamoDB for NoSQL datastore
- Elastic Load Balancer for HA
- VPC for protected access and subnets

![Photo Recognition Architecture](https://i.ibb.co/cXnXvc2/Arch-Diagram.jpg)

