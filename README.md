# DocuMind – AI-Powered PDF Document Assistant

DocuMind is an AI-powered PDF document assistant that allows users to upload PDF files and ask questions about their content. It uses Retrieval-Augmented Generation (RAG) to retrieve relevant information from documents and generate context-aware answers.

## Features

- Upload and process multiple PDF documents
- Extract text from PDF files
- Split documents into smaller chunks
- Generate semantic embeddings
- Store and search embeddings using FAISS
- Ask questions about uploaded documents
- Conversational memory for follow-up questions
- AI-generated document summaries
- Source and page references for answers
- Streamlit-based web interface

## Technologies Used

- Python
- LangChain
- Google Gemini
- FAISS
- Streamlit
- Sentence Transformers
- PyPDF2

## How It Works

PDF Upload  
↓  
Text Extraction  
↓  
Text Chunking  
↓  
Embeddings Generation  
↓  
FAISS Vector Database  
↓  
Relevant Information Retrieval  
↓  
Google Gemini  
↓  
AI-Generated Answer

## Project Structure

```text
DocuMind-AI-PDF-Assistant/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
└── src/
    ├── chat.py
    ├── config.py
    ├── processor.py
    └── embedding.py