# CHATBOT_BART

CHATBOT_BART is a Python notebook leveraging the Bard API for chatbot interactions, including question-answering and text summarization. It supports PDF extraction via PyPDF and integrates with Google Drive for seamless document processing and AI-driven responses.

## Features
- **Chatbot Interaction:** Uses Bard API for natural language understanding and response generation.
- **Text Summarization:** Summarizes extracted text from PDFs.
- **PDF Processing:** Extracts content from PDF files using PyPDF.
- **Google Drive Integration:** Enables storage and retrieval of documents.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CHATBOT_BART.git
   cd CHATBOT_BART
   ```
2. Install dependencies:
   ```bash
   pip install bardapi pypdf
   ```

## Usage
1. Set up the Bard API key:
   ```python
   import os
   os.environ['_BARD_API_KEY'] = "your_api_key_here"
   ```
2. Run the notebook and input queries for chatbot interactions or text summarization.
3. To process PDFs, upload them to Google Drive and specify the file path.

## Requirements
- Python 3.x
- Jupyter Notebook
- Bard API Key
- PyPDF

