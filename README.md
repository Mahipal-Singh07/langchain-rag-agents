# 🚀 LangChain RAG Agents

An advanced backend and AI engineering project focused on building intelligent, production-ready AI applications using **LangChain**, **LangGraph**, and **Retrieval-Augmented Generation (RAG)**. This repository demonstrates how modern AI systems can retrieve external knowledge, perform semantic search, orchestrate multi-step agent workflows, and interact with tools to provide accurate and context-aware responses.

---

## 📖 Overview

This project explores advanced AI backend concepts, including:

- Retrieval-Augmented Generation (RAG)
- Semantic Search
- AI Agents & Tool Calling
- LangGraph Workflows
- Vector Databases
- Embedding Models
- Document Processing Pipelines

The goal is to build scalable and intelligent AI-powered backend applications capable of reasoning over custom knowledge bases and interacting with external tools.

---

## 🛠️ Tech Stack

### Backend
- Node.js
- TypeScript

### AI Frameworks
- LangChain
- LangGraph

### Vector Database
- Qdrant

### LLM Providers
- Google Gemini
- Groq

### Embeddings
- Google Embeddings
- OpenAI Embeddings
- HuggingFace Embeddings

### Other Tools
- dotenv
- REST APIs
- Git & GitHub

---

## ✨ Key Features

### 🔍 Retrieval-Augmented Generation (RAG)

- Document ingestion and indexing
- Chunking and embedding generation
- Vector similarity search
- Context-aware response generation

### 🧠 Semantic Search

- Search documents using meaning instead of keywords
- Retrieve relevant information using vector embeddings
- Improve answer accuracy with contextual retrieval

### 🤖 AI Agents

- Tool-calling capabilities
- Multi-step reasoning workflows
- Dynamic decision-making
- Task execution through external tools

### 🔄 LangGraph Workflows

- Stateful AI agent execution
- Multi-node agent pipelines
- Conditional routing
- Agent orchestration and memory management

### 📄 Document Processing

- Load documents from multiple sources
- Transform and split content into chunks
- Generate embeddings
- Store and retrieve vectors efficiently

---

## 🏗️ Architecture

```text
User Query
    │
    ▼
LangGraph Agent
    │
    ├── Retrieve Context
    │        │
    │        ▼
    │    Qdrant Vector DB
    │
    ├── Tool Calling
    │
    └── LLM Reasoning
             │
             ▼
         Final Answer
```

---

## 🚀 Getting Started

### Clone Repository

```bash
git clone https://github.com/your-username/langchain-rag-agents.git

cd langchain-rag-agents
```

### Install Dependencies

```bash
npm install
```

### Environment Variables

Create a `.env` file in the root directory:

```env
GOOGLE_API_KEY=your_google_api_key

GROQ_API_KEY=your_groq_api_key

QDRANT_URL=your_qdrant_url

QDRANT_API_KEY=your_qdrant_api_key
```

### Run Development Server

```bash
npm run dev
```

### Build Project

```bash
npm run build
```

### Start Production Server

```bash
npm start
```

---

## 📂 Project Structure

```text
langchain-rag-agents/
│
├── src/
│   ├── agents/
│   ├── graph/
│   ├── tools/
│   ├── retrievers/
│   ├── embeddings/
│   ├── vectorstore/
│   └── services/
│
├── docs/
├── .env
├── package.json
├── tsconfig.json
└── README.md
```

---

## 🎯 Learning Outcomes

This project demonstrates:

- Building production-grade RAG systems
- Implementing semantic search pipelines
- Integrating vector databases with AI applications
- Developing AI agents with tool-calling capabilities
- Designing LangGraph workflows for complex reasoning tasks
- Creating scalable AI-powered backend architectures

---

## 📚 Concepts Covered

- Retrieval-Augmented Generation (RAG)
- Embeddings & Vector Search
- LangChain Fundamentals
- LangGraph State Management
- Agentic AI Systems
- Tool Calling
- Prompt Engineering
- Context Retrieval
- Knowledge Base Integration

---

## 🤝 Credits

Built as part of an **Advanced Backend + AI Engineering Course**, focusing on modern AI application development, agent architectures, retrieval systems, and scalable backend design patterns.

---

