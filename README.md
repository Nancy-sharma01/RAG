# RAG

Learning and building Retrieval-Augmented Generation (RAG) applications with Python, LangChain, vector databases, and LLMs.

## About

This repo is my hands-on learning project for understanding how RAG pipelines work end-to-end — from chunking and embedding documents, to storing them in a vector database, to retrieving relevant context and generating answers with an LLM.

## Tech Stack

- **Language:** Python (3.13)
- **Package management:** [uv](https://github.com/astral-sh/uv)
- **Framework:** LangChain
- **Vector database:**
- **LLM provider:** 

## Project Structure

```
RAG/
├── src/               # Application source code
├── pyproject.toml     # Project metadata and dependencies
├── uv.lock            # Locked dependency versions
├── .python-version     # Python version for uv
├── requirements.txt   # Dependency list (legacy/alternate)
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.13
- [uv](https://docs.astral.sh/uv/getting-started/installation/) installed

### Installation

```bash
git clone https://github.com/Nancy-sharma01/RAG.git
cd RAG
uv sync
```

### Environment Variables

Create a `.env` file in the project root with any API keys you need, e.g.:

```
OPENAI_API_KEY=your_key_here
```

### Running

```bash
uv run src/main.py
```

_(update this once you know your actual entry point)_

## What I'm Learning

- Document loading and chunking strategies
- Embedding generation
- Vector similarity search
- Prompt construction with retrieved context
- Evaluating RAG output quality

## Roadmap

- [ ] Basic RAG pipeline (load → chunk → embed → store → retrieve → generate)
- [ ] Add evaluation metrics
- [ ] Experiment with different chunking strategies
- [ ] Try multiple vector databases
- [ ] Add a simple UI (Streamlit?)

## License

This project is for personal learning purposes.
