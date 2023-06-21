# Farsi_PDF

# PDF OCR

This repository contains a Jupyter Notebook (`PDF_OCR.ipynb`) that converts PDF files into searchable PDFs using OCR (Optical Character Recognition) technology. 

## Requirements

To run the notebook, you need to install the following dependencies:

- `tesseract-ocr`: OCR engine for text recognition.
- `libtesseract-dev`: Development files for the Tesseract OCR library.
- `tesseract-ocr-fas`: Tesseract OCR language data for Persian (Farsi).
- `pytesseract`: Python wrapper for Tesseract OCR.
- `ghostscript`: Interpreter for the PostScript language and the PDF file format.
- `ocrmypdf`: Python tool to add OCR text to PDFs.

You can install these dependencies by running the following commands:

```bash
!apt install tesseract-ocr
!apt install libtesseract-dev
!apt-get install tesseract-ocr-fas
!pip install pytesseract
!apt install ghostscript
!pip install ocrmypdf==13.7.0
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/your-username/PDF-OCR.git
```

2. Move to the repository directory:

```bash
cd PDF-OCR
```

3. Launch Jupyter Notebook:

```bash
jupyter notebook
```

4. Open the `PDF_OCR.ipynb` notebook in your Jupyter environment.

5. Follow the instructions in the notebook to convert your PDF files to searchable PDFs using OCR.

Note: Make sure to place the PDF files you want to convert in the `input_papers` directory and the converted output files will be saved in the `output_papers` directory.

Feel free to customize the notebook as per your requirements and explore other features of the OCR tools used.

