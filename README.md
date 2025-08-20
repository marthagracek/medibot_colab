# Medical Chatbot

A medical information chatbot built with Retrieval-Augmented Generation (RAG) to answer healthcare questions using medical documents.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/marthagracek/medibot_colab/blob/main/medibot_prototype%20(1).ipynb)

## Features

- **Document Processing**: Processes medical PDFs and creates searchable knowledge base
- **Smart Search**: Uses vector embeddings for accurate information retrieval
- **Medical Safety**: Includes appropriate disclaimers and safety warnings
- **Interactive Chat**: User-friendly interface for asking medical questions

## Tech Stack

- **Language Model**: Google Gemini API
- **Framework**: LangChain
- **Vector Database**: ChromaDB
- **Embeddings**: HuggingFace Transformers
- **Interface**: Gradio
- **Development**: Google Colab

## Quick Start

1. **Open in Colab**: Click the badge above
2. **Add API Key**: Set your Gemini API key in Colab secrets as `MY_GEMINI_KEY`
3. **Upload Documents**: Add your medical PDF files
4. **Run All Cells**: Execute the notebook from top to bottom
5. **Start Chatting**: Use the generated interface to ask medical questions

## Setup

### Get Gemini API Key
1. Visit [Google AI Studio](https://makersuite.google.com/app/apikey)
2. Create a free API key
3. Add it to Colab secrets as `MY_GEMINI_KEY`

### Upload Medical Documents
- Use PDF format
- Upload through Colab's file upload interface
- The system will automatically process and index the content

## Usage Examples
