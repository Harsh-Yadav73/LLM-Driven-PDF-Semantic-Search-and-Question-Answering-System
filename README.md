# 📚 LLM-Driven-PDF-Semantic-Search-and-Question-Answering-System

A Retrieval-Augmented Generation (RAG) based AI system that allows users to upload a PDF or Word document and ask questions related to its content.

This project uses:
- Google Gemini API (for answer generation)
- Sentence Transformers (for embeddings)
- FAISS (for vector search)
- Python (Google Colab compatible)

---

## 🚀 Features

- 📄 Upload PDF or DOCX file
- 🔍 Extract document text automatically
- 🧠 Create semantic embeddings
- 📦 Store embeddings using FAISS vector database
- 🤖 Ask unlimited questions about the document
- ⚡ Uses Gemini API for intelligent responses

---

## 🏗️ Project Architecture

1. Document Upload
2. Text Extraction
3. Text Chunking
4. Embedding Generation
5. FAISS Vector Storage
6. Question Retrieval
7. Gemini Response Generation

---

## 🛠️ Technologies Used

- Python
- Google Generative AI (Gemini)
- Sentence Transformers
- FAISS
- PyPDF
- Docx2txt

---

## 📦 Installation

Run the following commands in Google Colab:

```python
!pip install google-generativeai
!pip install sentence-transformers
!pip install faiss-cpu
!pip install pypdf docx2txt
