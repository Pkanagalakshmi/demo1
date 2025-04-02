# Document Summarizer

A web application that allows users to upload documents (PDF, DOC, DOCX, or TXT) and get AI-generated summaries using OpenAI's GPT-3.5 model.

## Features

- Drag and drop file upload
- Support for multiple file formats (PDF, DOC, DOCX, TXT)
- Modern and responsive UI
- Real-time feedback and error handling
- Secure file handling

## Setup

1. Clone this repository:
```bash
git clone https://github.com/Pkanagalakshmi/demo1.git
cd demo1
```

2. Install the required dependencies:
```bash
pip install -r requirements.txt
```

3. Set up your OpenAI API key:
```bash
# On Windows
set OPENAI_API_KEY=your-api-key-here

# On Linux/Mac
export OPENAI_API_KEY=your-api-key-here
```

4. Run the application:
```bash
python app.py
```

5. Open your browser and navigate to `http://localhost:5000`

## Usage

1. Click the upload zone or drag and drop a document
2. Wait for the AI to generate a summary
3. View the generated summary below the upload zone

## Technical Details

- Backend: Python Flask
- Frontend: HTML, JavaScript, Tailwind CSS
- Document Processing: PyPDF2, python-docx
- AI: OpenAI GPT-3.5

## Notes

- Maximum file size: 16MB
- Supported file formats: PDF, DOC, DOCX, TXT
- Requires an OpenAI API key to function