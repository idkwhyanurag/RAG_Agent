# RAG Agent

A Retrieval-Augmented Generation (RAG) application built using **LangChain** and **Google Gemini** that answers questions using information retrieved from external documents instead of relying solely on the model's pre-trained knowledge.

---

## 🚀 Overview

Retrieval-Augmented Generation (RAG) combines semantic search with Large Language Models (LLMs) to provide more accurate, context-aware, and reliable responses.

This project demonstrates a complete RAG pipeline:

- Load and process documents
- Split text into chunks
- Generate embeddings
- Store embeddings in a vector database
- Retrieve relevant information
- Generate grounded responses using Gemini

---

## ✨ Features

- Document ingestion and preprocessing
- Text chunking
- Semantic search
- Retrieval-Augmented Generation (RAG)
- Google Gemini integration
- LangChain workflow
- Interactive Jupyter Notebook implementation
- Secure API key handling

---

## 🛠️ Tech Stack

- Python
- LangChain
- Google Gemini API
- Jupyter Notebook
- Vector Database
- Environment Variables (.env)

---

## 📂 Project Structure

```text
RAG_Agent/
│
├── agent.ipynb          # Main notebook
├── README.md
├── requirements.txt
└── .gitignore
```

---

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/idkwhyanurag/RAG_Agent.git
cd RAG_Agent
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate the Environment

#### macOS / Linux

```bash
source .venv/bin/activate
```

#### Windows

```bash
.venv\Scripts\activate
```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
GOOGLE_API_KEY=your_google_api_key
```

Never commit API keys or secrets to GitHub.

---

## ▶️ Usage

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
agent.ipynb
```

Run all cells and start querying your documents.

---

## 🔄 RAG Workflow

```text
Documents
    ↓
Text Splitting
    ↓
Embeddings
    ↓
Vector Store
    ↓
Retriever
    ↓
Relevant Context
    ↓
Gemini LLM
    ↓
Final Response
```

---

## 📚 Learning Outcomes

Through this project, I gained practical experience with:

- Retrieval-Augmented Generation (RAG)
- LangChain Framework
- Large Language Models (LLMs)
- Vector Embeddings
- Semantic Search
- Prompt Engineering
- AI Application Development

---

## 🔮 Future Improvements

- Streamlit Frontend
- Multi-document Support
- Chat History Memory
- Hybrid Search
- Source Citations
- Cloud Deployment

---

## 👨‍💻 Author

**Anurag Majumdar**

GitHub: https://github.com/idkwhyanurag

---

## ⭐ Acknowledgements

- LangChain
- Google Gemini
- Python Community
- Open Source AI Ecosystem