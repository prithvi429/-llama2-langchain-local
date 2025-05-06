# 🦙 llama2-langchain-local
Run LLaMA 2 locally and build intelligent agents with LangChain. This project includes Google Colab notebooks and setup instructions for deploying Meta’s LLaMA 2 model and integrating it with LangChain for advanced conversational AI applications.


# llama2-langchain-local

**Run Meta's LLaMA 2 locally and integrate it with LangChain for powerful conversational AI.**  
This repository provides Colab notebooks and setup instructions to deploy LLaMA 2 models and build intelligent agents using LangChain.

## 📁 Contents

- [`How_to_run_Llama_2.ipynb`](https://colab.research.google.com/drive/1ZkaGAmbKkoSeleSl4zl9RwXDtxxdXeY0?usp=sharing): Step-by-step guide to run LLaMA 2 locally, including model download, environment setup, and basic usage.
- [`Llama_2_LangChain.ipynb`](https://colab.research.google.com/drive/1Nai_feyBMcE0TQiuNEGwo8XnoWrfiURl?usp=sharing): Integrates LLaMA 2 with LangChain for conversational AI and agent workflows.

## 🛠 Requirements

- Python 3.8+
- Jupyter Notebook
- Hugging Face Transformers
- LangChain
- PyTorch
- SentenceTransformers
- `ctransformers` (for local LLaMA 2 inference)
- `faiss-cpu` (optional, for vector search)

Install with:

```bash
pip install transformers langchain torch sentence-transformers ctransformers faiss-cpu
