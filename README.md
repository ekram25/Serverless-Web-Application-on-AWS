# Serverless-Web-Application-on-AWS

## Project Description:

I built a serverless web application using AWS Lambda, API Gateway, DynamoDB, and S3. The application allowed users to create, read, update, and delete (CRUD) items from a DynamoDB table through a RESTful API.

### Project Architecture:
![img](https://github.com/user-attachments/assets/de8cf5ed-fbc6-42dd-b9f2-23e1e3e197f4)

### Steps to Build the Project:

* Create a DynamoDB table to store the items.
* Build a Lambda function to handle the CRUD operations on the DynamoDB table.
* Create an API Gateway RESTful API to interact with the Lambda function.
* Use S3 to store and host the web application's static files (HTML, CSS, and JavaScript).
* Create a CloudFront distribution to serve the S3-hosted static files with low latency.

### Tech Used:

* AWS Lambda: Handled the business logic and CRUD operations.
* API Gateway: Provided a RESTful API to interact with the Lambda function.
* DynamoDB: Stored and managed the items in the application.
* S3: Hosted the static files of the web application.
* CloudFront: Distributed and delivered the web application with low latency.
* AWS Route 53: Managed the DNS routing for the web application.
