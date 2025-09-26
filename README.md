# 📄 Chat with PDF using LangChain + Groq + Streamlit

A Streamlit-based AI-powered application that lets you **chat with your PDF files**.  
Simply upload one or more PDFs, ask a question, and the app will return context-aware answers generated using **LangChain**, **FAISS vector search**, **HuggingFace embeddings**, and **Groq’s LLaMA models**.

---

## ✨ Features
- 📂 Upload multiple PDF files at once
- 🔎 Extract and chunk text from PDFs
- 🧠 Generate embeddings using HuggingFace (`all-MiniLM-L6-v2`)
- 📚 Store and search PDF chunks with FAISS
- 🤖 Question-answering using **Groq LLaMA-3.3-70B Versatile**
- 🎨 Simple and interactive UI with Streamlit
- 🔐 API key management with `.env`

---

## 🚀 Tech Stack
- [Streamlit](https://streamlit.io/) – UI framework  
- [LangChain](https://www.langchain.com/) – LLM orchestration  
- [FAISS](https://github.com/facebookresearch/faiss) – Vector store  
- [HuggingFace Sentence Transformers](https://huggingface.co/sentence-transformers/all-MiniLM-L6-v2) – Embeddings  
- [PyPDF2](https://pypi.org/project/PyPDF2/) – PDF text extraction  
- [Groq](https://groq.com/) – LLaMA-powered LLM  
- [python-dotenv](https://pypi.org/project/python-dotenv/) – Environment variable management  

---

## ⚙️ Installation

1. **Clone this repository**
   ```bash
   git clone https://github.com/himasrikatam/ai_legal_assistant.git
   cd ai_legal_assistant
