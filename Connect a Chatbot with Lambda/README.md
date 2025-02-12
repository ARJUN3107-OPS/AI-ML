# BankerBot: A Simple Banking Chatbot

## Objective
This project demonstrates how to build a basic banking chatbot using **Amazon Lex** for conversation handling and **AWS Lambda** for backend processing. The chatbot can respond to user queries such as checking account balances.

## Steps

### 1. **Create an Amazon Lex Chatbot**
   - Define intents like `WelcomeIntent` and `CheckBalance`.
   - Configure sample utterances and enable code hooks.

### 2. **Deploy an AWS Lambda Function**
   - Write a simple function to return a random balance.
   - Link the Lambda function to the chatbot.

### 3. **Test the Chatbot**
   - Use the Lex test console to interact with the chatbot.
   - Validate that intents trigger correct responses.

## Things Learned
- How to define intents and utterances in Amazon Lex.
- How to integrate AWS Lambda for dynamic responses.
- How to fine-tune intent recognition and debug chatbot responses.

