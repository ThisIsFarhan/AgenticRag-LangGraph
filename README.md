# Simple Agentic RAG Implementation Using LangGraph

This repository contains an implementation of a Simple Agentic Retrieval-Augmented Generation (RAG) system using LangGraph. The agent follows a structured pipeline to answer user queries effectively.

## Workflow

The agent follows these steps:
1. **Retrieve Documents**: Fetch relevant documents based on the user's query.
2. **Grade Documents**: Assess the relevance of retrieved documents.
3. **Check Relevance**: If relevant documents are found, generate a response.
4. **Web Search (if needed)**: If no relevant documents are found, perform a web search before generating the response.

This structured approach ensures accurate and contextually relevant responses.

