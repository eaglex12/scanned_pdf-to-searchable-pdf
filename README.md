# PDF to Searchable PDF and Text Extractor

This Python script converts a multi-page PDF into images, performs OCR (Optical Character Recognition) on these images to create searchable PDFs, and extracts text into a combined text file. The script uses `ImageMagick` for PDF-to-image conversion and `Tesseract` for OCR.

## Prerequisites

- Python 3.x
- `ImageMagick` (for PDF to image conversion)
- `Tesseract` (for OCR)
- `PyPDF2` (for merging PDFs)
- Required Python libraries: `PyPDF2`

## Installation

1. **Install ImageMagick**:

   - For Windows: Download and install from [ImageMagick's website](https://imagemagick.org/script/download.php).
   - For macOS: Install via Homebrew:
     ```bash
     brew install imagemagick
     ```
   - For Linux: Install via package manager (e.g., `apt-get` for Debian-based systems):
     ```bash
     sudo apt-get install imagemagick
     ```

2. **Install Tesseract**:

   - For Windows: Download and install from [Tesseract's GitHub repository](https://github.com/tesseract-ocr/tesseract).
   - For macOS: Install via Homebrew:
     ```bash
     brew install tesseract
     ```
   - For Linux: Install via package manager:
     ```bash
     sudo apt-get install tesseract-ocr
     ```

3. **Install required Python libraries**:
   ```bash
   pip install PyPDF2
   ```
