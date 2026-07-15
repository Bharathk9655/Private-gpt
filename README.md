# Private-GPT with Ollama

Private-GPT is a privacy-first AI assistant that enables users to interact with Large Language Models (LLMs) entirely on their local machine. Built with Python, FastAPI, Gradio, and Ollama, the application supports Retrieval-Augmented Generation (RAG), semantic search, document summarization, and conversational AI without sending sensitive data to external servers.

---

## Features

- Local AI model execution using Ollama
- Retrieval-Augmented Generation (RAG)
- Semantic document search
- AI-powered document summarization
- Interactive chat interface
- Multiple file upload support
- FastAPI backend with Gradio frontend
- Support for Llama and Gemma models

---

## Technology Stack

**Backend**
- Python
- FastAPI
- Uvicorn

**Frontend**
- Gradio

**AI & ML**
- Ollama
- Llama
- Gemma
- PyTorch
- Embedding Models

**Libraries**
- Pandas
- NumPy
- HTTPX

---

## Project Structure

```
private-gpt/
│
├── private_gpt/
├── uploads/
├── embeddings/
├── requirements.txt
├── README.md
└── main.py
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/private-gpt.git
cd private-gpt
```

Create a virtual environment

```bash
python -m venv venv
```

Activate the environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

Install dependencies

```bash
pip install -r requirements.txt
```

---

## Install Ollama

Download Ollama from:

https://ollama.com

Pull the required model:

```bash
ollama pull llama3.2:3b-instruct-q4_K_M
```

or

```bash
ollama pull gemma3:1b
```

Verify installation

```bash
ollama list
```

---

## Run the Application

```bash
python -m poetry run python -m private_gpt
```

Open the application in your browser:

```
http://127.0.0.1:8001
```

---

## Application Workflow

```
User
   │
   ▼
Gradio Interface
   │
   ▼
FastAPI Backend
   │
   ▼
Ollama Model
   │
   ▼
Embedding Engine
   │
   ▼
RAG Pipeline
   │
   ▼
AI Response
```

---

## Supported Modes

- **RAG** – Context-aware question answering using uploaded documents
- **Search** – Semantic search across uploaded files
- **Basic Chat** – General conversation with the selected LLM
- **Summarize** – Generate summaries from uploaded documents

---

## Use Cases

- Enterprise Knowledge Assistant
- Internal Documentation Search
- Research Assistant
- HR and Policy Assistant
- Legal Document Analysis
- Secure AI Chatbot

---

## Skills Demonstrated

- Generative AI
- Retrieval-Augmented Generation (RAG)
- Ollama
- FastAPI
- Python
- Prompt Engineering
- Semantic Search
- Embedding Models
- Local LLM Deployment
- Gradio

---

## License

This project is intended for educational and research purposes.
