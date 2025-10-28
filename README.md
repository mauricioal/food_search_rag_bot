# Practice Project: Interactive Food Search and RAG Chatbot System
Estimated time needed: 120 minutes

## Interactive Food Search and RAG Chatbot System: Introduction
In this comprehensive lab, you will build an advanced food recommendation system that demonstrates three distinct approaches to similarity search and conversational AI. Using a rich food dataset with detailed nutritional information, ingredients, cooking methods, and taste profiles, you will create an interactive CLI search interface, implement advanced filtering techniques, and develop a RAG (Retrieval-Augmented Generation) chatbot that provides intelligent food recommendations using Chroma DB and natural language processing.

You will learn how to implement interactive user interfaces, metadata filtering, similarity scoring, and conversational AI systems that combine vector search with large language model responses. This lab demonstrates real-world applications of vector databases in creating intelligent recommendation systems and chatbots.

## Learning objectives
After completing this lab, you will be able to:

- Build interactive CLI interfaces for real-time food search and recommendation.
- Implement advanced search filtering with cuisine type, calorie restrictions, and ingredient matching.
- Create RAG systems that combine similarity search with natural language responses.
- Develop conversational chatbots that understand user queries and provide contextual food recommendations.
- Perform similarity search with dynamic filtering and real-time user interaction.
- Execute CRUD operations on vector databases with immediate search result updates.
- Understand chatbot conversation flow and user experience design.
- Implement CLI-based interfaces without external web frameworks.
- Compare traditional search results with AI-enhanced responses.
- Prerequisites
- Intermediate knowledge of Python programming
- Understanding of vector embeddings and similarity search concepts
- Basic knowledge of Chroma DB vector database operations
- Familiarity with command-line interfaces and user interaction patterns

# Setting up the Interactive Food Search Environment
Welcome to Part 1 of this comprehensive practice project. In this part, you will create three distinct food recommendation systems: an interactive CLI search interface, an advanced filtered search system, and an intelligent RAG chatbot that provides conversational food recommendations.

## A. Install the Required Packages

Install the required Python packages for Chroma DB, embeddings, and AI models. Execute the following commands in the terminal window:

pip install numpy==2.3.1

pip install scipy==1.16.0

pip install chromadb==1.0.12

pip install sentence-transformers==4.1.0

pip install ibm-watsonx-ai==1.3.24

### The packages provide:

- chromadb: Vector database for similarity search operations
- sentence-transformers: Text embedding generation for semantic search
- numpy: Numerical operations for similarity calculations
- ibm-watsonx-ai: IBM WatsonX AI SDK for RAG chatbot responses
