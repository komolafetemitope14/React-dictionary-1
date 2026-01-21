# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

SERVERLESS CLOUD DICTIONARY

This project is a serverless web application that allows users to search for cloud computing terms and view their definitions. It is built using AWS services and follows a fully serverless architecture.

The frontend is developed with React and hosted on AWS Amplify. All backend requests are handled through API Gateway and AWS Lambda, with DynamoDB used for storing cloud term definitions.

PROJECT OVERVIEW

The frontend is built using React and hosted on AWS Amplify.

User requests are routed through API Gateway to a Lambda function, which retrieves data from DynamoDB.

The application follows a fully serverless architecture with minimal infrastructure management.

SETUP OVERVIEW

Clone the project repository and install the required dependencies

Create a new GitHub repository and push the project code

Deploy the frontend using AWS Amplify

Create a DynamoDB table to store cloud terms and definitions

Upload the initial dataset using the AWS CLI

Create a Lambda function to fetch definitions from DynamoDB

Configure API Gateway to expose the Lambda function through a REST endpoint

Update the frontend with the API Gateway URL and redeploy

Each step requires basic AWS configuration and permissions setup.


HOW THE APPLICATION WORKS

The user searches for a cloud term

The request is sent to API Gateway

Lambda processes the request

DynamoDB returns the definition

The frontend displays the result


Live Application:
<img width="1791" height="841" alt="SAVED-1" src="https://github.com/user-attachments/assets/2ba61924-3674-446f-9e2b-5ad65cb5c52a" />



Architecture Diagram (Lucidchart):
<img width="1314" height="674" alt="Lucid-react" src="https://github.com/user-attachments/assets/b0cd9dd7-a02f-487f-aa83-dbe17cdbfd50" />

Technologies Used

AWS Amplify

AWS Lambda

AWS API Gateway

AWS DynamoDB

IAM

React



AUTHOR

Name: Komolafe Temitope


FUTURE ENHANCEMENT

Add more cloud terms

Improve search flexibility

Add categories

Enhance the UI
