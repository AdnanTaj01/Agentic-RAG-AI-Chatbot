# Agentic RAG AI Chatbot

This project is an AI-powered chatbot built using LangGraph, Streamlit, and Retrieval-Augmented Generation (RAG) concepts. It demonstrates how to create an interactive conversational AI application that can respond using external knowledge sources and tool-based workflows.

## Project Goal

The main objective of this project is to build an intelligent chatbot that can:
- understand user queries,
- retrieve relevant information,
- use LangGraph-based workflow logic,
- provide responses through a simple Streamlit web interface.

## What This Project Achieves

This repository shows how to build an agentic chatbot with the following capabilities:

- LangGraph-based backend workflow for conversational logic
- Multiple backend variants for different use cases
- Streamlit frontend for interactive user experience
- Support for tool-based and database-based chatbot flows
- RAG-style knowledge retrieval integration
- Modular project structure for better organization and scalability

## Project Structure

- src/backend/ : backend logic files for different LangGraph implementations
- src/frontend/ : Streamlit frontend files
- config/ : dependency and configuration files
- docs/ : documentation and structure notes
- tests/ : test-related folder for future validation

## Main Features

### 1. LangGraph Backend
The project includes several backend implementations such as:
- basic LangGraph workflow
- database-backed chatbot backend
- MCP-based backend
- tool-based backend
- RAG-based backend

### 2. Streamlit Frontend
A user-friendly web interface is provided using Streamlit so users can interact with the chatbot easily.

### 3. Agentic AI Workflow
The system is designed to follow an agentic approach where the chatbot can reason through steps and use tools or retrieved context for better responses.

### 4. RAG Integration
The project demonstrates how retrieval-based augmentation can improve chatbot answers by using relevant information from external content.

## Technologies Used

- Python
- LangGraph
- Streamlit
- RAG concepts
- LangChain-style workflow patterns

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the desired frontend or backend file using Python.

3. Open the Streamlit interface in your browser.

## Summary

This project is a practical example of building an industry-style AI chatbot application using modern agentic workflows, retrieval augmentation, and a clean project structure.
