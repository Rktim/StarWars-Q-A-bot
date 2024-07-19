# Star Wars Q&A Chatbot

Welcome to the Star Wars Q&A Chatbot project! This project aims to create an interactive chatbot that can answer questions about Star Wars characters using Langchain and the Cohere LLM.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Collection](#data-collection)
3. [Chatbot Development](#chatbot-development)
4. [User Interaction](#user-interaction)
5. [Key Features](#key-features)
6. [Contributing](#contributing)


## Introduction
This project is a Star Wars Q&A chatbot built using Langchain and the Cohere Language Learning Model (LLM). The chatbot is designed to provide information about various Star Wars characters based on data scraped from the Star Wars Fandom Wiki.

## Data Collection
- **Web Scraping:** Information about Star Wars characters is gathered using web scraping techniques.
- **Data Content:** The data includes character names, titles, and descriptions.
- **Storage:** The scraped data is stored in a Pandas DataFrame and saved as a CSV file for easy access and manipulation.

## Chatbot Development
- **Langchain:** Used to create a conversational AI chain.
- **Chat Prompt Template:** A system message introduces the chatbot as a Star Wars expert, and a human message template handles user questions.
- **Cohere LLM:** Integrated as the language model for generating responses.
- **LLMChain Object:** Combines the LLM and the chat prompt template to handle user interactions.

## User Interaction
- **Chat Interface:** Implemented to allow users to ask questions about Star Wars characters.
- **Question Processing:** The user's question is passed to the LLMChain, which generates a response based on the scraped data and the LLM's knowledge.
- **Continuous Interaction:** The chatbot continues to interact with the user until they type 'exit'.

## Key Features
- **Web Scraping:** Efficient data acquisition from the Star Wars Fandom Wiki.
- **Langchain Integration:** Builds a robust conversational AI chain.
- **Cohere LLM:** Provides natural language understanding and response generation.
- **Interactive Chat Interface:** Engages users in a seamless conversation.


## Contributing
Contributions are welcome! If you have any suggestions or improvements, please open an issue or submit a pull request.


May the Force be with you!
