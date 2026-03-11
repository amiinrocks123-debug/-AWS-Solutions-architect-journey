AWS Lambda Serverless Lab
Overview

This project demonstrates how to create and deploy a serverless function using AWS Lambda. AWS Lambda allows developers to run code without provisioning or managing servers. The function executes automatically in response to events.

Objectives

The goal of this lab was to understand the fundamentals of serverless computing and how AWS Lambda integrates with other AWS services.

AWS Services Used

Amazon Web Services

AWS Lambda

Amazon CloudWatch

AWS IAM

Architecture

The Lambda function is triggered manually from the AWS console and executes code in a managed runtime environment. AWS automatically handles scaling, infrastructure management, and logging.

Architecture Flow:

User Trigger
   ↓
AWS Lambda Function
   ↓
CloudWatch Logs
Steps Performed

Navigated to the AWS Lambda console

Clicked Create Function

Selected Author from Scratch

Configured the following:

Runtime: Python

Function name: hello-lambda-function

Created an execution role using IAM

Wrote a basic Lambda function

Deployed and tested the function

Verified logs inside CloudWatch
Key Concepts Learned

Serverless computing

Event-driven architecture

IAM roles for Lambda permissions

Monitoring using CloudWatch logs

Lambda runtime environments
