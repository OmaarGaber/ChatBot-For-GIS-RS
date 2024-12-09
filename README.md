# ChatBot-For-GIS-RS
The chatbot ( Bob )answers questions about GIS &amp; RS using Python with nltk_ut, json, torch, and numpy. It utilizes natural language processing to understand user queries and provides accurate responses based on complex GIS &amp; RS concepts.

# Chatbot Project

## Overview
This chatbot project is designed to provide conversational responses based on user input. It utilizes Natural Language Processing (NLP) techniques and a neural network model to understand and respond to various queries.

## Features
- **Intent Recognition**: The chatbot recognizes different user intents based on predefined patterns.
- **Custom Responses**: It provides tailored responses for each identified intent.
- **Training Capability**: The model can be trained with new intents and responses.

## Technologies Used
- Python
- PyTorch
- NLTK (Natural Language Toolkit)
- JSON for data handling

## Project Structure
├── intents.json # Contains intents, patterns, and responses
├── model.py # Defines the neural network architecture
├── nltk_ut.py # Utility functions for tokenization and stemming
├── training.py # Script to train the model
├── chat.py # Main script to run the chatbot
└── data.pth # Saved model state and metadata

## Installation
Install required packages:
    pip install -r requirements.txt

Download the NLTK punkt tokenizer:
    import nltk
    nltk.download('punkt')

Usage
  Train the model:
      Run training.py to train the chatbot on the intents specified in intents.json.

Start the chatbot:
      Run chat.py to interact with the chatbot.
      python chat.py
