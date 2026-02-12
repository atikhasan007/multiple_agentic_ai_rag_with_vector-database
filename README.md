# 📄 PDF Knowledge Base AI Assistant (Phi + pgvector + PostgreSQL)

This project builds a **CLI-based AI Assistant** that can answer questions from a PDF document using **Phi Framework**, **PostgreSQL + pgvector**, and **Groq API**. The assistant loads a PDF from a URL, converts it into embeddings, stores them in a vector database, and allows interactive querying from the terminal.

---

## 🚀 Features

- 📚 Load knowledge from PDF URLs  
- 🧠 Vector search using pgvector  
- 💬 Persistent chat history with PostgreSQL  
- ⚡ Fast LLM inference with Groq  
- 🖥️ Interactive CLI interface  
- 🔁 Resume previous sessions  

---

## 🛠️ Tech Stack

- Python  
- Phi Framework  
- PostgreSQL  
- pgvector  
- Docker  
- Typer (CLI)  
- Groq API  

---

## 📦 Project Structure

```bash
.
├── main.py
├── .env
├── requirements.txt
└── README.md

🔗 **Documentation:** [Read the Docs](https://docs.phidata.com/vectordb/pgvector)
