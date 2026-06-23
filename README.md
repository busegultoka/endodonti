# endodonti
Endodonti Alanında Yapay Zeka Destekli Klinik Asistan(RAG ve Fine-Tuning  Karşılaştırmalı) – Doğal Dil İşleme

Endodontic Question Answering System
Project Description

This project is a domain-specific question answering system developed for the field of Endodontics. The system combines Retrieval-Augmented Generation (RAG), LoRA-based Fine-Tuning, and a Hybrid Architecture to generate reliable answers based on academic resources.

Features
RAG-based document retrieval
LoRA Fine-Tuning on Mistral-7B
Hybrid (RAG + Fine-Tuning) architecture
FAISS vector database
FastAPI backend
Web-based user interface
Endodontic terminology support
Technologies
Python
Mistral-7B-Instruct-v0.2
LoRA (PEFT)
FAISS
Sentence Transformers
FastAPI
HTML/CSS/JavaScript
Project Structure
project/
│
├── data/
├── outputs/
├── rag/
├── finetuning/
├── api/
├── web/
├── notebooks/
└── README.md
Results
Best Embedding Model: BGE-Large
Fine-Tuned Mistral Keyword Hit Rate: 51.9%
Hybrid Model achieved the highest semantic similarity scores.
