# 🐝📄 RAG-Hive — AI Document Chatbot

**RAG-Hive** is a Streamlit-based AI application that allows users to upload documents (PDF, DOCX, TXT) and interact with them using natural language queries.

It uses a **Retrieval-Augmented Generation (RAG)** pipeline powered by **Llama-3.2-1B-Instruct** to retrieve relevant context from documents and generate accurate, context-aware answers.

---

## 🚀 Features

- 📂 Upload multiple documents (PDF, DOCX, TXT)  
- 🔍 Ask questions in natural language  
- 🧠 Context-aware answers using RAG pipeline  
- ⚡ Fast semantic search with FAISS  
- 💬 Interactive chat interface with history  
- 🎨 Clean and modern UI built with Streamlit  
- 🔄 Efficient processing (documents processed once per session)  

---

## 🧠 How It Works

1. 📄 Documents are uploaded and text is extracted  
2. ✂️ Text is split into smaller chunks  
3. 🔢 Embeddings are created using Sentence Transformers  
4. 📦 FAISS vector store is built  
5. 🔎 Relevant chunks are retrieved based on user query  
6. 🤖 Llama model generates answer using retrieved context  

---

## 🛠️ Tech Stack  

- **Language:** Python  
- **Frontend/UI:** Streamlit  
- **LLM:** Llama-3.2-1B-Instruct (Hugging Face)  
- **Framework:** LangChain  
- **Embeddings:** Sentence Transformers  
- **Vector DB:** FAISS  
- **Deep Learning:** PyTorch, Transformers  
- **Document Processing:** PDFPlumber, python-docx  
- **Deployment:** pyngrok  

  
---

## 💻 How to Run 

Use the following link on Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1eqot5FEVAH_2Lot-uKvgAQH1_hSQsviG?usp=sharing)


