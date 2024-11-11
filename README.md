# Medical Literature Review Generator

A web application that automatically generates literature reviews from medical PDF documents using AI.

## Features

- Upload medical PDF documents
- Extract text content from PDFs
- Generate comprehensive literature reviews using AI
- Clean and responsive web interface
- Support for large documents (up to 16MB)

## Installation

1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```

## Usage

1. Open the web interface in your browser
2. Upload a medical PDF document
3. Click "Generate Review"
4. Wait for the AI to process the document
5. View the generated literature review

## Technologies Used

- Flask (Web Framework)
- PDFPlumber (PDF Text Extraction)
- Hugging Face Transformers (AI Model)
- BART Large CNN (Summarization Model)