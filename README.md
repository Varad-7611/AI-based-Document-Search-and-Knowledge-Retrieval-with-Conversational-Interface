# 📄 AI Based Document Search and Knowledge Retrieval with Conversational Interface

An AI-powered document search and conversational question-answering system that enables users to upload documents and interact with them through a chat-based interface. The system uses semantic search and retrieval-augmented generation (RAG) to ensure accurate, context-aware responses strictly based on the uploaded content.

---

## 🚀 Features

- Upload and process multiple **PDF** and **TXT** documents  
- Semantic search using vector embeddings  
- Conversational question-answering interface  
- Answers restricted strictly to document context (no hallucinations)  
- OCR fallback for scanned or image-based PDFs  
- Modern dark UI with smooth hover effects  
- Fast and efficient vector search using **ChromaDB**  
- Modular and scalable architecture  

---

## 🧠 Technology Stack

- **Frontend**: Streamlit  
- **LLM**: Meta LLaMA 3.2 Instruct (Hugging Face)  
- **Embeddings**: sentence-transformers/all-MiniLM-L6-v2  
- **Vector Database**: ChromaDB  
- **Framework**: LangChain  
- **PDF Processing**: PyPDF2, Unstructured  

---

## ⚙️ Installation

### Clone the Repository
```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
