# MedicalPatients-Project

## Project Overview
This project is focused on automating the process of extracting key information from medical prescriptions stored in PDF format. The PDFs are first converted to images, followed by text extraction using Optical Character Recognition (OCR) and regular expressions to parse and structure the required details.

## Objective
To extract key data such as doctor name, patient name, prescription date, address, medications, and refill details from PDF prescriptions by converting them into images, applying preprocessing steps, and using text extraction and regular expressions.

## Tools & Technologies Used

Python Libraries:
pdf2image: To convert PDF files into images.
Pillow: For image processing and saving the output.
OpenCV: For image preprocessing and thresholding.
PyTesseract: For OCR (Optical Character Recognition) to extract text from images.
re: For parsing text using regular expressions.
Tesseract-OCR: OCR engine for extracting text from images.
Poppler: A PDF rendering library to assist with the conversion of PDF to images.
Operating System: macOS

## Project Workflow

Converting PDF files to Images: Using pdf2image to convert each page of a PDF into an image.
Image Preprocessing: Preprocessing the images using OpenCV to improve OCR accuracy.
Extracting Text from Images: Extracting text from preprocessed images using pytesseract.
Applying Regular Expressions: Using regular expressions to identify and extract key data from the text.
Saving Extracted Data: Saving the extracted data into separate .txt files for each processed image.
