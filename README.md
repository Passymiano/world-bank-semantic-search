# 🌍 World Bank Semantic Search
### An AI-powered knowledge base for MDB project portfolio discovery

A lightweight RAG pipeline that ingests real World Bank project data, embeds it using a sentence-transformer model, and enables natural language search across 100+ projects — returning results by **meaning**, not just keywords.

> Built as a practical demonstration of the core architecture behind AI-powered portfolio knowledge systems used by multilateral development banks (MDBs).

---

## What it does

Type a question like *"green finance and climate investment in Africa"* and the system finds the most relevant World Bank projects — even if they use completely different words in their descriptions.

---

## How it maps to real MDB workflows

| This project | MDB Portfolio Knowledge System |
|---|---|
| World Bank public API ingestion | Acquiring and ingesting MDB project data from public sources |
| Clean, structure, standardise fields | Standardising project data into a consistent format |
| Sentence-transformer embeddings | Vector search and similarity matching |
| ChromaDB vector store | Semantic search and information retrieval |
| Natural language query interface | AI-powered project discovery |
| Documented, reproducible notebook | Knowledge transfer and documentation |

---

## Tech stack

| Tool | Purpose |
|---|---|
| `requests` | Scraping data from the World Bank Projects API |
| `pandas` | Cleaning and structuring the dataset |
| `sentence-transformers` | Generating semantic embeddings |
| `chromadb` | Vector similarity search |
| Python 3 / Google Colab | No local setup required |

---

## How to run

1. Open [Google Colab](https://colab.research.google.com)
2. Click **File → Upload notebook** and select `mdb_knowledge_search.ipynb`
3. Click **Runtime → Run all**

No API keys required. Fully free.

---

## Key findings

- **100 active World Bank projects** indexed
- **$16.7 billion** total portfolio value
- **Average project size:** $166.7 million
- Top countries: India, Bangladesh, Morocco, Turkiye, Rwanda, Togo, The Gambia
- Sector metadata was sparse in this API snapshot — a real data quality finding relevant to MDB knowledge base work

---

## Author

**Passy Miano** — Data & AI Analyst
[LinkedIn](https://linkedin.com/in/passy-miano) | [GitHub](https://github.com/Passymiano)
Nairobi, Kenya
