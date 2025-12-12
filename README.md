**🩺 AI Medical Chatbot**
An AI-powered medical question-answering chatbot using RAG, Grok API, and HuggingFace embeddings.
⚠️ This project is for educational/demo purposes only and is NOT a substitute for professional medical advice.

✨ Features
**RAG (Retrieval-Augmented Generation)** to fetch the most relevant information from your medical dataset
**Grok API** for high-quality natural language responses
**HuggingFace-based embedding** + chunking for fast & accurate retrieval
**Memory system** for context-aware conversations
Answers general medical queries such as:
 “What are the symptoms of cancer?”
 “How to treat typhoid?”
 “Causes of migraine?”
Fully modular structure (easy to extend)

**🧠 How It Works (Architecture)**

  User Query
      ↓
  Chunked + Embedded Medical Data (HuggingFace)
      ↓
  Retriever (RAG) → Fetch top relevant chunks
      ↓
  Grok LLM → Generate final answer using context
      ↓
  Response to User

**📂 Project Structure**
├── medibot.py                    
├── connect_memory_with_llm.py   
├── create_memory_for_llm.py      
├── requirements.txt              
├── pyproject.toml               
├── uv.lock                       
├── .gitignore
└── LICENSE

**🛠️ Tech Stack**
 Python 3.10+
 UV (virtual environment + dependency manager)
 RAG (Retrieval-Augmented Generation)
 LangChain
 Grok API
 HuggingFace Embeddings
 Local text/medical dataset

**⚖️ Disclaimer**
 This chatbot is a learning project and provides general medical information.
 It cannot diagnose diseases or replace professional doctors.
