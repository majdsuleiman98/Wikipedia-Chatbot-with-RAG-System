# Wikipedia-Chatbot-with-RAG-System

This project is a Retrieval-Augmented Generation (RAG) system that allows users to chat with Wikipedia articles on specific topics. By leveraging **FAISS** for vector-based document retrieval and the **Flan-T5** language model for natural language generation, this chatbot can retrieve, generate, and summarize information interactively. **LangChain** is used to manage conversation history with a summary memory, ensuring coherent dialogue flow.

## Project Overview

- **Vector Database**: **FAISS** (Facebook AI Similarity Search) enables efficient similarity search and dense vector storage, helping to retrieve relevant Wikipedia snippets based on user queries.
- **Language Model**: Google’s **Flan-T5** model is used for generating human-like responses based on retrieved information, enabling more natural and informative conversations.
- **Chat Management**: **LangChain’s ConversationSummaryMemory** stores and manages conversation history, creating a seamless chat experience where context is preserved across multiple turns.

## Features

- **Topic Selection**: Choose a specific Wikipedia topic to explore.
- **Conversational Chat**: Ask questions and receive answers based on Wikipedia content, enhanced by the language model for readability and context.
- **Conversation History**: Maintains and summarizes conversation history using **ConversationSummaryMemory** from LangChain to ensure smooth, coherent dialogue.
