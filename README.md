🚀 AI Strategic Analyst Agent (RAG-Based)
Project Overview
This project demonstrates an end-to-end Retrieval-Augmented Generation (RAG) pipeline designed for enterprise document intelligence. The agent acts as a Senior AI Strategy Consultant, transforming raw business documents into structured executive reports.

Key Features
Intelligent Extraction: Uses an automated workflow to ingest PDFs or text-based agreements.

Vectorized Memory: Implements a Simple Vector Store and Embeddings (OpenAI) to retrieve contextually relevant data for analysis.

Strategic Persona: Programmed with custom System Prompts to enforce MBA-level analysis focusing on risk mitigation and strategic growth.

Structured Output: Automatically generates a three-pillar report consisting of:

Summary

Key Risks

Actionable Recommendations

Technical Stack
Orchestration: n8n (Low-code workflow automation)

LLM: OpenAI GPT-4

Database: Simple Vector Store for RAG-based retrieval

Memory: Simple Memory for contextual chat persistence

How it Works
Input: User uploads a document or pastes text into the n8n Chat Interface.

Processing: The system splits text into chunks using the Recursive Character Text Splitter and stores them in a vector database.

Analysis: The AI Agent queries the database and applies strategic logic to the retrieved content.

Delivery: A structured report is provided back to the user in real-time.
