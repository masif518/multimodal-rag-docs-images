# Multimodal RAG: Question Answering over Documents & Images

This project implements a **Multimodal Retrieval-Augmented Generation (RAG)** system that answers user questions using information from **PDF documents and images**.

The system supports:
- Text extraction from PDFs
- OCR-based text extraction from images
- Semantic search using embeddings and FAISS
- Context-aware answer generation using a Large Language Model (LLM)

---

## 🚀 Features

- 📄 PDF text extraction using PyMuPDF  
- 🖼️ Image text extraction using Tesseract OCR  
- 🔍 Semantic retrieval using SentenceTransformers + FAISS  
- 🧠 LLM-based answering using a Retrieval-Augmented approach  
- ☁️ Fully runnable on Google Colab  

---

## 🏗️ Architecture

PDFs + Images
↓
Text Extraction + OCR
↓
Embeddings (SentenceTransformers)
↓
FAISS Vector Store
↓
Context Retrieval
↓
LLM Prompting (RAG)
↓
Answer


---

## 🛠️ Tech Stack

- Python
- Google Colab
- PyMuPDF
- Tesseract OCR
- SentenceTransformers
- FAISS
- Hugging Face Transformers

---

## 📒 How to Run

1. Open the notebook in **Google Colab**
2. Upload PDFs and images when prompted
3. Run cells top to bottom
4. Ask questions over your documents and images

---

## 💡 Example Use Cases

- Summarizing reports with charts
- Understanding scanned documents
- Question answering over mixed document types
- Multimodal knowledge retrieval

---

## 📌 Notes

- Implemented manual RAG logic to avoid framework version drift
- Designed to be lightweight and CPU-friendly

---

## 👤 Author

**Masif Ahmed**
