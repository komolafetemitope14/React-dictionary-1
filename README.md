# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Serverless Cloud Dictionary

This project is a Serverless Cloud Dictionary Application built using AWS services.
It allows users to search for cloud technology terms and instantly view their definitions through a simple web interface.

The application follows a serverless architecture, meaning there are no traditional servers to manage. All backend services are handled by AWS.

🔗 Project Links

GitHub Repository:
https://github.com/your-username/your-repo-name

Live Application (AWS Amplify):
https://your-app-name.amplifyapp.com

Architecture Diagram (Lucidchart):
https://lucid.app/your-diagram-link

🛠️ Technologies Used

AWS Amplify – Hosts the React frontend

AWS Lambda – Handles backend logic

AWS API Gateway – Manages API requests

AWS DynamoDB – Stores cloud terms and definitions

IAM – Manages access and security

✨ Features

Search for cloud-related terms

View clear and simple definitions

Fast, serverless backend

Secure AWS infrastructure

Publicly accessible web app

📂 Project Overview

The frontend is built with React and hosted on AWS Amplify.
User requests are sent through API Gateway, which triggers an AWS Lambda function.
The Lambda function fetches the requested term from DynamoDB and returns the definition to the user.

This design keeps the application lightweight, scalable, and easy to maintain.

🚀 How It Works

The user enters a cloud term in the web app

The request is sent to API Gateway

Lambda processes the request

DynamoDB returns the definition

The result is shown to the user

🌱 Future Improvements

Add more cloud terms

Improve search flexibility

Add categories for terms

Enhance the UI

🧹 Clean-Up (Optional)

When the project is no longer needed, AWS resources such as Lambda, DynamoDB, API Gateway, Amplify, and IAM roles can be deleted to avoid unnecessary charges.
