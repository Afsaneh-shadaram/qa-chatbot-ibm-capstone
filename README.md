# QA Bot using LangChain + RAG + IBM Watsonx

## Project Overview

This project is a capstone assignment for the IBM course: Generative AI Applications with RAG and LangChain.

The goal is to build an intelligent Question Answering (QA) Bot that uses LangChain and Large Language Models (LLMs) to answer questions based on uploaded PDF documents.

Instead of manually searching through large documents, this system allows users to ask natural language questions and receive accurate answers extracted directly from document content.

This repository includes the full implementation in Python along with the screenshots.

## Demo

<img width="983" height="658" alt="Gradio_inputs" src="https://github.com/user-attachments/assets/9f2e5df4-b1cf-4966-b166-61d5ad85668e" />


<img width="968" height="865" alt="Gradio_output" src="https://github.com/user-attachments/assets/7267e566-d18e-443d-9fc6-39e25a90d721" />



## Architecture Components

The system is built using the following components:

* 📄 Document Loader – Loads PDF files (pypdf)
* ✂️ Text Splitter – Breaks documents into smaller chunks
* 🔢 Embedding Model – Converts text into vector representations
* 🗄️ Vector Database (ChromaDB) – Stores embeddings for fast retrieval
* 🔎 Retriever – Finds relevant document sections using similarity search
* 🤖 LLM (IBM Watsonx.ai) – Generates final answers
* 🌐 Gradio UI – Provides an interactive user interface
  
## Required Libraries

Before running the project, install the required dependencies:

* gradio → builds interactive web UI
* ibm-watsonx-ai → provides access to IBM LLM models
* langchain → core framework for LLM applications
* langchain-ibm → IBM integrations for LangChain
* langchain-community → additional LangChain tools
* chromadb → vector database for embeddings
* pypdf → loads PDF documents

## Summary

This project demonstrates how Retrieval-Augmented Generation (RAG) can be used to build intelligent assistants that answer questions based on private documents, combining:

* LangChain pipelines
* Vector databases
* IBM Watsonx LLMs
* Interactive UI with Gradio
  

