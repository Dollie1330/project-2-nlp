# Customer Support Chatbot for Online Shopping

## Project Overview

This chatbot is designed to assist customers with common queries related to an online shopping platform. It covers questions about order tracking, return policies, product information, and delivery times using Natural Language Processing techniques.

## Workflow Steps

- The chatbot's FAQ dataset is created as a Python DataFrame within the Colab notebook.
- User queries are preprocessed using spaCy for tokenization, lemmatization, and stopword removal.
- A rule-based intent matching system using keywords classifies the query intent.
- Based on the recognized intent, the chatbot returns the appropriate response.
- An interactive loop allows users to ask questions and receive answers continuously.

## How to Use

1. Run all cells in the provided Colab notebook sequentially.
2. Enter customer support queries in the input prompt.
3. Receive automated responses based on predefined intent and response mapping.
4. Type "exit" to quit the chat session.

## Libraries Used

- pandas
- spaCy

## Customization and Extensions

- Additional intents and responses may be added to cover more queries.
- Advanced intent detection with machine learning models can be implemented.
- Integrate Named Entity Recognition (NER) to handle dynamic information like order numbers.
- Deploy the chatbot using Flask or Streamlit with a web interface.
- Link the chatbot with real-time order and product databases for live support.

## Project Submission

Host your notebook and code on GitHub along with this README file, and submit the repository link as per instructions.
