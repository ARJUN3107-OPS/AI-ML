Amazon Lex Chatbot with Custom Slots

 Overview
This project demonstrates the use of Amazon Lex to build an interactive chatbot that greets users and handles tasks like checking account balances. The chatbot is designed with custom slots to capture specific user inputs, ensuring accurate and dynamic responses.

 Features
- Intents & Utterances: Defined multiple intents and sample utterances to handle user queries effectively.
- Fallback Intent: Improved user experience by handling unexpected inputs dynamically.
- Custom Slots: Captures specific user inputs such as account numbers or types to provide personalized responses.
- Integration: The chatbot can be integrated with other AWS services for scalability and extended functionality.

 What is Amazon Lex?
Amazon Lex is a service for building conversational interfaces using voice and text. It provides Natural Language Processing (NLP) and Automatic Speech Recognition (ASR), making it useful for customer support, virtual assistants, and other AI-driven interactions.

 Project Highlights
- Custom Slot Implementation: Created a custom slot type with predefined values to enhance accuracy in capturing user input.
- Intent-Slot Connection: Associated custom slots with the CheckBalance intent to retrieve account balance information accurately.
- Utterance Handling: Incorporated slot values within utterances for a more natural and dynamic user experience.

 Unexpected Learnings
One surprising aspect of the project was the importance of Fallback Intent variations. By adding multiple fallback responses, the chatbot's interactions felt more natural and engaging, even when it couldn't fully understand the user's input.

 Time Taken
The project took approximately 2 hours to complete, including setup, intent configuration, slot creation, and chatbot testing.

 Example Utterances
Here are some example utterances that the chatbot can understand:
- "Check my balance for account [account number]"
- "What's the balance on my [account type] account?"

 How to Run This Project
1. Set Up Amazon Lex: Go to the AWS Console and create a new Amazon Lex bot.
2. Define Intents & Utterances: Add user intents like `CheckBalance` and configure sample utterances.
3. Create Custom Slots: Define slot types with specific values (e.g., account numbers, account types).
4. Test the Chatbot: Use the built-in Amazon Lex tester to validate responses.
5. Integrate with AWS Services (Optional): Connect the chatbot to Lambda, DynamoDB, or an API Gateway for extended functionality.



