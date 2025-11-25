# n8n RAG Customer Support Agents

This repository contains two complete RAG agents built using n8n, OpenAI, Pinecone, Gmail, and Google Drive. These automations deliver AI powered customer support with retrieval based answers, document ingestion, and smart email handling.

## Included Workflows

### 1. Customer Support Agent
- Listens to incoming messages in Gmail
- Extracts intent and routes messages
- Retrieves context from Pinecone vector store populated with Policy and FAQ documents
- Uses OpenAI to generate accurate replies based on retrieved context
- Sends responses back to customers through Gmail

### 2. Product Query Agent
- Monitors a Google Drive folder for new PDF or text documents
- Splits, embeds, and stores documents inside Pinecone FAQ namespace
- Provides retrieval augmented answers to product questions through an AI agent

## Files

- **Customer Support Agent.json**  
- **Product Query Agent.json**  
- **Policy and FAQ Document.pdf**  
- **N8n Demo Video.mp4**

## Tech Stack

- n8n
- OpenAI embeddings and chat models
- Pinecone vector database
- Gmail API
- Google Drive API

## Author

Built by Naresh Mandla  
Product Manager building AI automations, RAG agents, and SaaS workflows.
