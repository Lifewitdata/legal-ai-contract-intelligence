# Legal AI Contract Intelligence Platform

## Overview

An end-to-end Legal AI platform built using the CUAD (Contract Understanding Atticus Dataset) to automate contract analysis, clause understanding, semantic search, and legal document intelligence.

The project combines Natural Language Processing (NLP), Legal-BERT, Named Entity Recognition (NER), and FAISS-based semantic retrieval to help legal teams analyze contracts more efficiently.

---

## Business Problem

Legal professionals spend significant time reviewing contracts to identify:

* Termination clauses
* Confidentiality agreements
* Payment terms
* Governing law
* Liability clauses
* Renewal provisions

This project demonstrates how AI can automate contract understanding and retrieval.

---

## Dataset

Dataset Used: CUAD (Contract Understanding Atticus Dataset)

Features:

* 500+ real commercial contracts
* 13,000+ legal annotations
* 41 legal clause categories
* Expert-labeled legal documents

---

## Project Pipeline

### 1. Data Ingestion

* Loaded CUAD JSON dataset
* Parsed contract metadata
* Extracted contract text

### 2. Data Cleaning

* Removed invalid contracts
* Calculated contract lengths
* Performed quality checks

### 3. Exploratory Data Analysis

* Contract length distribution
* Clause frequency analysis
* Outlier detection
* Summary statistics

### 4. Named Entity Recognition (NER)

Using SpaCy:

* Organizations
* Dates
* Monetary values
* Locations

### 5. Legal-BERT Integration

Model:

* nlpaueb/legal-bert-base-uncased

Tasks:

* Legal text representation
* Contract clause understanding
* Legal NLP experimentation

### 6. Semantic Search

Using:

* Sentence Transformers
* FAISS Vector Index

Capabilities:

* Semantic contract retrieval
* Similar clause discovery
* Legal document search

---

## Tech Stack

### Programming

* Python

### NLP

* SpaCy
* Transformers
* Sentence Transformers

### Machine Learning

* PyTorch
* Hugging Face

### Search

* FAISS

### Data Analysis

* Pandas
* NumPy

### Visualization

* Matplotlib
* Seaborn

---

## Project Structure

```text
legal-ai-contract-intelligence/
│
├── notebooks/
│   └── Legal_AI_Project.ipynb
│
├── data/
│
├── models/
│
├── faiss/
│
├── src/
│
├── requirements.txt
│
└── README.md
```

---

## Key Outcomes

* Built a legal document analysis pipeline
* Implemented Named Entity Recognition on contract text
* Integrated Legal-BERT for legal language understanding
* Developed FAISS-based semantic search over contracts
* Created a foundation for a Legal RAG Assistant

---

## Future Improvements

* Fine-tune Legal-BERT on clause classification
* Build Legal RAG Assistant
* Deploy FastAPI service

---

## Author

Isfaque Ansari

Data Analyst | NLP Enthusiast | Aspiring Data Scientist
