## RAG Chatbot Application

## Introduction
This project implements a Context-Aware Retrieval-Augmented Generation (RAG) chatbot using Streamlit. The chatbot combines cutting-edge natural language processing with efficient information retrieval to deliver intelligent, context-sensitive responses. It is powered by the Mistral-7B-Instruct-v0.3 language model, a state-of-the-art AI capable of understanding and generating human-like text. The system is integrated with ChromaDB, a high-performance vector database, enabling rapid and relevant information retrieval to augment the chatbot's responses. This architecture allows the chatbot to provide more accurate, informative, and contextually appropriate answers by leveraging both its language understanding capabilities and a vast knowledge base.

## Hugging Face Model

## Features

1. **Contextual Responses**: The chatbot retrieves relevant documents from a knowledge base and uses them to provide contextual responses to user queries.
2. **Conversational History**: The chatbot maintains a conversation history, allowing it to reference and build upon previous interactions.
3. **Document Management**: The application provides a document management interface, allowing users to upload and store new documents in the knowledge base.
4. **Feedback Mechanism**: Users can provide feedback on the chatbot's responses, which is used to improve the quality of future responses.

## Dependencies
The project relies on the following major dependencies:
- `streamlit`
- `huggingface_hub`
- `langchain`
- `chromadb`
