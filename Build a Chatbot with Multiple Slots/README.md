 Banking Query Chatbot with Amazon Lex

This project demonstrates building a banking query chatbot using Amazon Lex, AWS Lambda, and AWS CloudFormation. The chatbot handles common customer queries like account balance, transaction history, loan information, and funds transfer.

 Features

 Intents:
     `CheckBalance`: Retrieves account balance.
     `GetTransactions`: Fetches recent transaction history.
     `LoanInformation`: Provides details on loans.
     `TransferFunds`: Handles money transfers between accounts.
 Slots:
     `AccountNumber`: Captures and validates account numbers.
     `Amount`: Handles monetary values for transfers.
 Lambda Integration:  Lambda functions process the intents and interact with a backend banking system (simulated in this project).
 CloudFormation: Automates the deployment of Lex bots and Lambda functions for consistent and scalable infrastructure.

 Challenges

 Integration with Banking Systems: Mapping intents and ensuring smooth communication between Lambda functions and the database required careful consideration.

 Project Timeline

 Initial Chatbot Setup: ~2 hours
 CloudFormation Automation: ~10 minutes

 Error Encountered

 Lambda Function Not Attached: After initial deployment, the Lambda function was not correctly linked to the intent, causing the bot to fail. This was resolved by re-attaching the function and redeploying.

 Key Learnings

 Multiple Slot Usage: The `TransferFunds` intent showcases using the same slot type (`AccountNumber`) multiple times to capture both source and destination accounts.
 Confirmation Prompts: Implementing confirmation prompts enhances accuracy by verifying user inputs before processing.
 Lex Features: Explored Lex's conversation flow feature and visual builder for designing and managing chatbot interactions.
 CloudFormation Automation: Learned to define and provision AWS infrastructure using CloudFormation templates, ensuring repeatability and scalability.

This project provides a solid foundation for building more complex and feature-rich conversational interfaces for banking and other domains.
