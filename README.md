


#######youtube link of my project:https://youtu.be/ioygKIHLBD0

# Serverless Quiz Application with AWS DynamoDB and Lambda

A serverless quiz application built using Amazon Web Services (AWS). The project uses AWS Lambda for backend business logic, Amazon DynamoDB for data storage, and Amazon API Gateway to expose REST APIs.

## Project Overview

The Serverless Quiz Application is designed to provide an interactive quiz experience for education, training, and entertainment.

The application follows a serverless architecture where AWS Lambda handles the backend logic without requiring traditional server management. Amazon DynamoDB is used as the NoSQL database for storing quiz data, while API Gateway provides REST APIs for communication between the frontend and backend.

## Technologies Used

- AWS Lambda
- Amazon DynamoDB
- Amazon API Gateway
- AWS IAM
- Python / Node.js
- HTML
- CSS
- JavaScript
- REST APIs
- NoSQL Database

## AWS Services Used

### AWS Lambda

AWS Lambda is used to implement the backend business logic of the application. Lambda functions handle tasks such as retrieving quiz questions, validating answers, calculating scores, and processing user responses.

### Amazon DynamoDB

DynamoDB is used as the NoSQL database for storing quiz questions, answers, user responses, and related information.

### Amazon API Gateway

API Gateway is used to create and expose REST API endpoints that allow the frontend to communicate with the Lambda functions.

### AWS IAM

AWS IAM is used to manage permissions and control access between Lambda and other AWS resources.

## Application Architecture

```text
             User
               |
               v
     Web Frontend
   HTML / CSS / JavaScript
               |
               v
       Amazon API Gateway
               |
               v
          AWS Lambda
               |
               v
       Amazon DynamoDB
