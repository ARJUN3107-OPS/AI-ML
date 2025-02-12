# Save User Info with Your Chatbot

## Objective
This project demonstrates how to build a chatbot using **Amazon Lex** that can store and use user session information through context tags. The chatbot helps users check their bank balance and handle follow-up inquiries efficiently.

## Steps

### 1. **Create an Amazon Lex Chatbot**
   - Define intents like `CheckBalance` and `FollowupCheckBalance`.
   - Configure sample utterances and add custom slot types.

### 2. **Implement Context Tags**
   - Use session attributes to store user information across interactions.
   - Create an input context (`contextCheckBalance`) to manage follow-up intents.

### 3. **Deploy an AWS Lambda Function**
   - Write a function to process balance inquiries and return dynamic responses.
   - Link the Lambda function to the chatbot intents.

### 4. **Test the Chatbot**
   - Use the Lex test console to verify conversation flow and context handling.
   - Ensure `FollowupCheckBalance` intent triggers correctly only after `CheckBalance`.

## Things Learned
- How to use context tags to maintain session-based user information.
- How to set up follow-up intents for a seamless conversational experience.
- How to integrate **AWS Lambda** with **Amazon Lex** for backend processing.
