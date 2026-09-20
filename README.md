# 🔍 Kestrel Labs Multi-Agent Research Assistant

An AI-powered multi-agent research assistant built using LangGraph, Groq LLMs, ChromaDB, Sentence Transformers, and Gradio.

This project retrieves relevant information from Kestrel Labs documents, verifies the retrieved content, and generates research-based answers through an interactive chatbot.

## 🚀 Project Overview

The Kestrel Labs Multi-Agent Research Assistant uses multiple specialized AI agents to perform document-based research.

The system combines query routing, research planning, semantic retrieval, answer verification, response synthesis, and citation validation into a single workflow.

Users can interact with the assistant through a Gradio-based chatbot interface and ask questions about the Kestrel Labs document collection.

## ✨ Features

- 🤖 Multi-agent research workflow
- 🧭 Intelligent query routing
- 📝 Research planning
- 🔎 Semantic document retrieval
- 🗄️ ChromaDB vector database
- 🧠 Conversation memory
- ✅ Answer verification
- 📚 Citation validation
- 💬 Interactive Gradio chatbot
- 📄 Document-based question answering

## 🏗️ Multi-Agent Architecture

The project consists of the following agents:

### 1. Router Agent

Identifies the type of user query and routes it through the appropriate research workflow.

### 2. Conversation Memory Agent

Maintains relevant conversation context to support follow-up questions and multi-turn conversations.

### 3. Planner Agent

Creates a research plan based on the user's question.

### 4. Retriever Agent

Retrieves relevant document chunks from the ChromaDB vector database using semantic similarity search.

### 5. Verifier Agent

Checks the retrieved information and evaluates whether it supports the research question.

### 6. Synthesizer Agent

Combines the retrieved information into a clear and structured final answer.

### 7. Citation Validator

Checks the citations and validates the references used in the generated response.
