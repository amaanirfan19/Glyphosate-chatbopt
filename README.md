# Pesticide Chatbot

The **Medical Literature Chatbot** is an intelligent assistant designed to interact with medical literature documents. It leverages the power of LangChain, Cohere API, and Streamlit to provide relevant information, answer questions, and assist users in their medical research.

## Features

- **Document Retrieval**: The chatbot retrieves medical literature documents using LangChain's document loading capabilities.
- **Contextual Responses**: Cohere API, acting as an LLM, generates context-aware responses based on user queries.
- **User-Friendly Interface**: The Streamlit frontend provides an intuitive interface for users to interact with the chatbot.

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/amaanirfan19/Glyphosate-chatbot.git
    ```

2. Install the necessary dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up your environment variables:
    - Create a `.env` file with the following keys:
        - `LANGCHAIN_API_KEY`: Your LangChain API key.
        - `COHERE_API_KEY`: Your Cohere API key.

4. Run the chatbot using Streamlit:

    ```bash
    streamlit run app.py
    ```

5. Interact with the chatbot by typing medical queries or prompts related to specific topics.
