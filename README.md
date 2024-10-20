Chatbot_py
This repository contains a simple chatbot built using OpenAI's GPT-2 model. The chatbot can have basic conversations with users and maintain context across multiple turns. The project leverages the pre-trained GPT-2 model from the `transformers` library by Hugging Face.
## Features

- Console-Based Interaction: The chatbot runs in the console, allowing for easy testing and interaction.
- Predefined Responses: The chatbot includes some predefined responses for common questions.
- Context Tracking: The chatbot maintains conversation context to make the conversation more coherent.

## Requirements

- Python 3.6+
- PyTorch
- Transformers library by Hugging Face

## Installation

1. Clone the repository:
2. Navigate to the project directory:
3. Install the required packages:

## Running the Chatbot

To start the chatbot, run the following command:

The chatbot will start in the console. You can type your messages, and the chatbot will respond. To exit the conversation, type `exit`.

## Usage

- Type a message and press Enter to receive a response from the GPT-2 chatbot.
- The chatbot can handle predefined intents like "hello", "how are you", "bye", and "what is your name".
- The chatbot also generates responses using GPT-2 for other user inputs, while keeping track of the conversation history.

## Example Interaction

## License

This project is licensed under the MIT License.
