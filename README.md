# Receipt Scanner and Categorizer

This is a Python-based receipt scanning and categorization system that uses Optical Character Recognition (OCR) to process receipts. The system extracts details such as merchant name, total amount, and expense category (e.g., Groceries, Dining, etc.) from receipts. It supports both uploading an image or capturing a live image using a webcam.

## Features:
- **OCR-based Text Extraction**: Uses [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) for extracting text from receipt images.
- **Receipt Categorization**: Categorizes receipts into predefined categories such as Groceries, Dining, Shopping, etc.
- **Merchant Name Extraction**: Heuristic-based extraction of the merchant name from the receipt.
- **Live Capture Mode**: Capture receipts using a webcam for real-time processing.
- **Regular Expressions for Amount Detection**: Extracts the total amount from the receipt using regex.

## Requirements:

To run this project, make sure you have the following dependencies installed:

1. Python 3.x
2. `pytesseract` (OCR tool)
3. `opencv-python` (for webcam capture)
4. `Pillow` (for image processing)
5. `transformers` (for LayoutLMv3 model)
6. `torch` (for deep learning models)

You can install the required dependencies by running:

```bash
pip install pytesseract opencv-python Pillow transformers torch

