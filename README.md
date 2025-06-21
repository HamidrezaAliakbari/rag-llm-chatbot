
# rag-llm-chatbot

A Retrieval-Augmented Generation Q&A assistant (Week 1) built with LangChain + FAISS/Chroma (or Pinecone) and a hosted LLM.

## 📂 Structure

- `notebooks/week1-rag-chatbot.ipynb` – Colab-ready demo notebook  
- `src/` – modular code:
  - `ingestion.py`  – PDF/webpage chunking  
  - `embeddings.py` – embedding generator (FAISS/Chroma client)  
  - `retrieval.py`  – vector-store search wrapper  
  - `chat.py`       – LangChain chain & prompt templates  
- `data/`     – sample PDFs & webpages  
- `examples/` – sample Q&A inputs & outputs  
- `.github/workflows/` – (optional) CI configs  
- `requirements.txt` – pinned dependencies  

## 🚀 Quick start

```bash
# install deps
pip install -r requirements.txt
