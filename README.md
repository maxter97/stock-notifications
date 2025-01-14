# Stock Notification System 
Project 2 for DevOp Challenge #DevOpsAllStarsChallenge
## Overview
Creating a stock notification system to send real-time data on your favorte stocks to users thought email and/or text.

<img width="853" alt="Screenshot 2025-01-13 at 11 19 16 AM" src="https://github.com/user-attachments/assets/97457744-d683-463b-87ea-fa2a9b1ae5c6" />

## Prerequisites
1. Familiar with AWS and Python
2. An AWS Account 
3. API Key from Alpha Vantage or any stock market API
4. A Code/Text Editor: To edit any code if needed
## Instruction
### 1. Obtian an API key from Alpha Vantage
Sign up at https://www.alphavantage.co/support/#api-key for a free tier key.
Make sure to save the key for later in the project
### 2. Create a AWS SNS Topic
Selcet Standard for type and name(ex.stock_topic) your topic. Then hit create Topic. Save the ARN for the topic to use for later
### 3. Create SNS Policy and Role for Lambda 
### 4. Create Lambda function
### 5. Create subscription for SNS topic and subscribe to it
### 6. Add Code and Environment Varialbes to Lambda fuction 
### 7. Test and Deploy Code 
### (Optional) Configure EventBridge Schedule to receive Notifcations at a certain period of time

## What was learned 
Create an SNS topic for users to subscribe too
Setting up SNS to send messaseges 
Create a Lambda function
Using code and environment varialbes inside an Lambda fuction 
Adding policys and roles to Lambda 
Retirving data from an api and changing it to a readable format
Tesing before delpoying your code 
## Future Improvements
Have a link users and click to subsribe 
Have a way to enter what stocks they want to see outside of changing the code inside the fuction 
