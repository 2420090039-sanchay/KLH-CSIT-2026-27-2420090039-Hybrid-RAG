# Hybrid RAG-Based Intelligent Document Question Answering

> AI Driven Language Technologies (ADLT) Course Mini Project
> Department of Computer Science & Engineering | KLH University

---

# 📌 Course Project Information

**Course:** AI Driven Language Technologies (ADLT)

**Project Title:**
**Hybrid RAG-Based Intelligent Document Question Answering**

This repository contains the implementation, documentation, experiments, results, and project deliverables for a Hybrid Retrieval-Augmented Generation (RAG) based document question-answering system developed as part of the AI Driven Language Technologies course.

---

# 👨‍💻 Team Members

| Name                | Roll Number |
| ------------------- | ----------- |
| Agastya Singh       | 2420030690  |
| M HariHaran         | 2420030243  |
| Challa Saketh Kumar | 2420030618  |
| Sanchay Krishna G   | 2420090039  |

---

# 👨‍🏫 Faculty

**Dr. K. Swanthana**
Department of Computer Science & Engineering
KLH University

---

# 📖 Project Abstract

The project focuses on developing a **Hybrid Retrieval-Augmented Generation (RAG)** system for intelligent document question answering. The system allows users to upload documents and ask natural-language questions based on their content.

The system combines **BM25 keyword-based retrieval** with **semantic vector retrieval using FAISS and Sentence Transformers** to identify relevant document sections. The retrieved information is provided as context to a Large Language Model (LLM), which generates context-aware answers along with relevant source information.

The mini project focuses on implementing the core Hybrid RAG pipeline, including document processing, chunking, embedding generation, retrieval, context generation, and question answering.

---

# 🎯 Project Objectives

* Upload and process documents
* Extract and preprocess document text
* Split documents into meaningful chunks
* Generate semantic embeddings
* Store embeddings using FAISS
* Create a BM25 keyword index
* Implement Hybrid Retrieval
* Generate context-aware answers using an LLM
* Display relevant source information
* Provide an interactive document question-answering interface

---

# 🛠️ Technologies Used

* Python
* LangChain
* FAISS
* BM25
* Sentence Transformers
* Hugging Face Transformers
* Llama / Mistral
* Streamlit
* Git
* GitHub

---

# 📂 Repository Structure

```text
.
├── src/
├── docs/
├── data/
├── results/
├── reports/
├── README.md
├── requirements.txt
└── .gitignore
```

### Folder Description

**src/**
Contains the main source code for document processing, chunking, embeddings, retrieval, and question answering.

**docs/**
Contains architecture diagrams, literature survey, research notes, and technical documentation.

**data/**
Contains sample documents, datasets, and dataset-related information.

**results/**
Contains screenshots, experimental results, and system outputs.

**reports/**
Contains project reports, presentations, and review submissions.

---

# ⚙️ Getting Started

### Clone the Repository

```bash
git clone https://github.com/<username>/<repository-name>.git
```

### Navigate to the Repository

```bash
cd <repository-name>
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

> Setup instructions may be updated as implementation progresses.

---

# 🔄 Hybrid RAG Pipeline

```text
Documents
    ↓
Text Extraction
    ↓
Document Chunking
    ↓
 ┌───────────────────────┐
 │                       │
BM25 Retrieval     Semantic Retrieval
 │                       │
 └───────────┬───────────┘
             ↓
      Hybrid Retrieval
             ↓
     Relevant Context
             ↓
          LLM
             ↓
      Generated Answer
```

---

# 📅 Development Status

| Phase                       | Status         |
| --------------------------- | -------------- |
| Project Planning            | ✅ Completed    |
| Literature Survey           | ✅ Completed    |
| Research Gap Identification | ✅ Completed    |
| System Architecture         | 🔄 In Progress |
| Document Processing         | ⏳ Upcoming     |
| Hybrid Retrieval            | ⏳ Upcoming     |
| LLM Integration             | ⏳ Upcoming     |
| Testing & Evaluation        | ⏳ Upcoming     |

---

# 📊 Expected Outcomes

* Effective document-based question answering
* Combination of keyword and semantic retrieval
* Improved retrieval of relevant document information
* Context-aware LLM responses
* Source-aware answers
* Interactive document analysis interface

---

# 📌 Repository Guidelines

* Maintain meaningful commits throughout development.
* Each team member contributes using their own GitHub account.
* Document important development phases.
* Maintain organized project folders.
* Do not upload API keys or credentials.
* Do not upload confidential datasets.
* Keep `requirements.txt` updated when dependencies change.

---

# 📄 Acknowledgement

This repository is maintained as part of the **AI Driven Language Technologies (ADLT)** course offered by the Department of Computer Science & Engineering, KLH University.

The repository serves as the central workspace for the development, documentation, experimentation, evaluation, and submission of the Hybrid RAG mini project.
