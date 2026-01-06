# Academic Research Assistant using RAG

This project implements an **Academic Retrieval-Augmented Generation (RAG)** system that enables question answering over research papers and technical PDFs.  
The system retrieves relevant academic content using semantic search and generates **grounded, clean, and readable answers** using an open-source language model.

---

## 🔍 Project Overview

Large Language Models often hallucinate or lack access to domain-specific knowledge contained in research papers.  
This project addresses that limitation by combining document retrieval with language generation, ensuring that answers are strictly grounded in academic sources.

The system is designed to work with **research papers, surveys, and technical PDFs**, making it suitable for academic and research-focused use cases.

---

## 🧠 Key Features

- Academic PDF ingestion and parsing  
- Text chunking optimized for research documents  
- Sentence-transformer embeddings for semantic understanding  
- FAISS-based vector search for efficient retrieval  
- Open-source LLM (no API key or billing required)  
- PDF noise handling (hyphenation, bullets, table references)  
- Academic-style, hallucination-controlled answers  

---

## 🏗️ System Architecture

```
PDF Documents
      ↓
Text Extraction & Cleaning
      ↓
Chunking
      ↓
Embeddings (Sentence Transformers)
      ↓
FAISS Vector Store
      ↓
Relevant Context Retrieval
      ↓
Prompt + Open-Source LLM
      ↓
Grounded Academic Answer
```

---

## 📁 Project Structure

```
academic-rag/
├── notebook/
│   └── academic_rag_colab.ipynb
├── src/
│   ├── preprocessing.py
│   └── rag_pipeline.py
├── data/
│   └── README.md
├── requirements.txt
└── README.md
```

---

## 📚 Dataset

The system is designed to work with **academic research papers**, including:

- NLP and transformer survey papers  
- Speech processing and clinical AI research  
- Open-access arXiv PDFs  

Due to copyright considerations, **PDF files are not included** in this repository.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/academic-rag.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:
   ```bash
   academic_rag_colab.ipynb
   ```
4. Upload your academic PDFs and start asking questions.

---

## 🧪 Example Query

**Question:**  
> How are transformers used in speech processing?

**Answer (example):**  
Automatic speech recognition, neural speech synthesis, speech translation, speech enhancement, multimodal applications, and spoken dialogue systems.

---

## 🧰 Technologies Used

- Python  
- LangChain (LCEL)  
- FAISS  
- Sentence Transformers  
- Hugging Face Transformers  
- Google Colab  

---

## 📌 Future Improvements

- In-text citations for answers  
- Chat-based user interface  
- Support for larger document collections  
- Evaluation metrics for RAG quality  

---

## 👤 Author

**Your Name**  
MSc Data Science  
