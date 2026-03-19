# LlamaIndex

A hands-on learning project exploring [LlamaIndex](https://www.llamaindex.ai/) — a framework for building LLM-powered applications with RAG (Retrieval-Augmented Generation), vector stores, and multiple LLM/embedding integrations.

---

## 🚀 Features

- LLM integrations: **OpenAI**, **Anthropic (Claude)**, **AWS Bedrock**
- Embedding integrations: **OpenAI**, **HuggingFace**, **AWS Bedrock**
- Vector store integrations: **ChromaDB**, **Qdrant**
- Document loaders for PDF, DOCX, HTML, and more
- Reranking with **Cohere**
- Jupyter notebooks for interactive exploration

---

## 📁 Project Structure

```
llamaIndex/
├── 01_setup_and_basics.ipynb   # Setup and basics notebook
├── main.py                     # Entry point
├── pyproject.toml              # Project metadata and dependencies
├── requirements.txt            # Pip-installable dependencies
├── .env.example                # Environment variable template
├── .python-version             # Python version pin
└── uv.lock                     # Locked dependency versions
```

---

## ⚙️ Setup

### Prerequisites
- Python >= 3.13
- [uv](https://github.com/astral-sh/uv) (recommended) or pip

### 1. Clone the repository
```bash
git clone https://github.com/Satyanarayana06b/llamaIndex.git
cd llamaIndex
```

### 2. Create and activate virtual environment
```bash
uv venv
.venv\Scripts\activate   # Windows
```

### 3. Install dependencies
```bash
uv pip install -r requirements.txt
```

### 4. Configure environment variables
```bash
cp .env.example .env
```
Edit `.env` and fill in your API keys:
```
OPENAI_API_KEY=your_openai_api_key
AWS_BEARER_TOKEN_BEDROCK=your_aws_bearer_token
AWS_DEFAULT_REGION=us-east-1
```

---

## 🏃 Running

```bash
python main.py
```

Or open the Jupyter notebooks:
```bash
jupyter notebook
```

---

## 🛠️ Tech Stack

| Category | Libraries |
|----------|-----------|
| Framework | `llama-index`, `llama-index-core` |
| LLMs | OpenAI, Anthropic, AWS Bedrock |
| Embeddings | OpenAI, HuggingFace, AWS Bedrock |
| Vector Stores | ChromaDB, Qdrant |
| Document Loaders | pypdf, python-docx, beautifulsoup4 |
| Reranking | Cohere |
| Notebooks | Jupyter, ipywidgets |
| Data | pandas, numpy, matplotlib |

---

## 📄 License

This project is for learning and experimentation purposes.

