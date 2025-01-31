# {Under construction}Document Sacn Management System

## Overview
This is a Python-based document management system that uses machine learning to classify documents, allows user labeling and retraining, integrates OCR for text extraction, and provides a frontend for system operations and reports.

## Features
- Unsupervised learning to group PDF documents by similarity
- Interactive labeling and model retraining
- OCR for extracting text from marked sections in documents
- Folder monitoring and secure file handling
- SQL database integration for metadata storage
- Web frontend for labeling, reports, and system operations

## Directory Structure
- `docs/`: Documentation files
- `src/`: Source code
  - `main.py`: Entry point for the application
  - `clustering.py`: Unsupervised learning and clustering
  - `ocr.py`: OCR text extraction
  - `database.py`: Database integration
  - `encryption.py`: File encryption
  - `monitoring.py`: Folder monitoring
  - `webapp/`: Flask web application
    - `app.py`: Flask app setup
    - `templates/`: HTML templates
    - `static/`: Static files (CSS, JS)
- `tests/`: Unit tests
- `.gitignore`: Git ignore file
- `LICENSE`: MIT License file
- `setup.py`: Setup script for packaging
- `requirements.txt`: Python dependencies
- `README.md`: Project overview and instructions

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/document-management-system.git
   cd document-management-system
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Install Tesseract OCR
   For ubuntu
   ```bash
   sudo apt install tesseract-ocr
   ```
   For macOS
   ```bash
   brew install tesseract
   ```

## Usage
1. Run the application
   ```bash
   python src/main.py
   ```
2. Open your browser and navigate to `http://127.0.0.1:5000` to access the web frontend.

# License
This project is licensed under the **MIT License** - see the **LICENSE** file for details.

# Contributing
Please read **CONTRIBUTING.md** for details on our code of conduct and the process for submitting pull requests.

# Acknowledgements
* Scikit-learn
* Tesseract OCR
* Flask

# Contact
For any inquiries, please contact [your-email@example.com].