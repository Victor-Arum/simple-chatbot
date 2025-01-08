# simple-chatbot

This project features a simple chatbot designed to assist Adidas customers with various inquiries, including payment methods, order tracking, returns, refunds, and more. Built using natural language processing (NLP) and machine learning, the chatbot provides quick and helpful responses to improve the customer experience.

## Steps to run the program
- Open main.py.
- Install necessary libraries and tools.
- Run main.py.
- Open and running predict.py.
- Interact with the chatbot window.

## Project Files
1. adidas_chatbot.json
- This file contains the chatbot’s intent dataset.
- Defines categories like greetings, payments, order tracking, returns, and refunds.
- Includes patterns (user queries) and responses for each intent, enabling the chatbot to understand and respond to customer questions effectively​

2. chatbot_model.h5
- The trained neural network model for the chatbot.
- Encodes the relationships between input queries and corresponding responses using the dataset.
- Used to predict the appropriate response during runtime.

3. classes.pkl
- Serialized Python object storing the list of intents (classes) from the dataset.
- Helps the chatbot map user inputs to specific intents.

4. words.pkl
- Serialized Python object storing the tokenized vocabulary from the dataset.
- Used to preprocess user input and prepare it for the chatbot model.
  
5. main.py
- The main script to initialize and launch the chatbot.
- Sets up the necessary components, loads the trained model, and starts the interaction process.
  
6. predict.py
- A script that processes user input during runtime.
- Uses the trained model to predict the intent of the user query and generate an appropriate response.
  
7. Steps to run the chatbot.doc
- Documentation outlining the steps to set up and run the chatbot​.
