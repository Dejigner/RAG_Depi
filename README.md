# PDF Question Answering System

A Streamlit-based application that allows users to upload PDF documents and ask questions about their content using a RAG (Retrieval-Augmented Generation) pipeline.

## Features

- PDF document upload and processing
- Text extraction and chunking
- Semantic search using FAISS
- Question answering using TinyLlama model
- Clean and intuitive user interface

## Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd <repo-name>
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the Streamlit app:
```bash
streamlit run app.py
```

2. Open your web browser and navigate to the provided local URL (typically http://localhost:8501)

3. Upload a PDF document and ask questions about its content

## Requirements

- Python 3.8+
- PyPDF2
- Streamlit
- PyTorch
- Transformers
- Sentence Transformers
- FAISS
- Other dependencies listed in requirements.txt

## Project Structure

- `app.py`: Main Streamlit application
- `requirements.txt`: Project dependencies
- `README.md`: Project documentation 