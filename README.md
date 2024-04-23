# Persian OCR 

## Project Description
This project is an Optical Character Recognition (OCR) system designed to recognize and digitize Persian text from images. It uses Tesseract OCR engine enhanced with tools and libraries like pytesseract, OpenCV, and PIL for image processing. This system can be especially useful for converting printed Persian texts into editable formats. Additionally, it features integration with a Telegram bot to receive images and return the recognized text directly to the user.

## Technologies Used
- Python 3
- pytesseract
- OpenCV (cv2)
- PIL (Pillow)
- Tesseract OCR
- python-telegram-bot

## Features
- Image preprocessing to enhance OCR accuracy:
  - Resizing images to improve detail recognition
  - Noise removal and smoothing
  - Rotation correction to adjust text alignment
  - (Optional) Line removal for processing tabular data
- Telegram bot interface for easy interaction and OCR processing on the go
- Supports both local and remote image processing

## Installation
Before running the project, ensure you have Python installed along with pip. Then, follow these steps:

1. Install Tesseract OCR and the Persian language data:
   ```bash
   sudo apt install tesseract-ocr
   sudo apt-get install tesseract-ocr-fas
2. Install the required Python libraries:
  ```bash
  pip install pytesseract Pillow opencv-python-headless pdf2image python-telegram-bot==13.3 telethon

To use the OCR system, you can either run the script locally to process images stored on your machine or interact via the Telegram bot.
Please feel free to fork the repository, make your changes, and submit a pull request.
