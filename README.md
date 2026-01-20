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
```
---

## 🧪 How It Works

1. User uploads **PDF** or **TXT** documents  
2. Text is extracted using **PyPDF2** (with OCR fallback for scanned PDFs)  
3. Text is split into smaller chunks  
4. Vector embeddings are generated using **MiniLM**  
5. Embeddings are stored in **ChromaDB**  
6. Relevant chunks are retrieved for each user query  
7. The **LLaMA** model generates a response strictly from the retrieved context  

---

## 💬 Usage

1. Upload one or more documents  
2. Click **Process Documents**  
3. Ask questions using the chat input  
4. Receive accurate answers based only on document content  

If the answer is not found in the documents, the system responds with:

> **"I don't know"**

---

## 🌐 Deployment (Streamlit Cloud)

1. Push the project to GitHub  
2. Go to **https://streamlit.io/cloud**  
3. Connect your GitHub repository  
4. Add `HF_TOKEN` under **Secrets**  
5. Deploy the application  

---

## 🎯 Use Cases

- Academic research and study assistance  
- Knowledge-base chatbots  
- Document and report analysis  
- Legal and policy document exploration  
- Resume and portfolio document querying  

---


