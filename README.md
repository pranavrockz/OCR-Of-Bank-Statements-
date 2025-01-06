# OCR-Of-Bank-Statements
This repository contains a project focused on the optical character recognition (OCR) of bank statements. The goal is to extract relevant data from scanned or digital bank statements, such as transaction details, balance, dates, and other key information.

Project Overview
The project applies OCR techniques to extract text and structured information from bank statements and classify it into structured fields. It leverages machine learning algorithms to process and analyze the OCR data for further use cases like fraud detection, account analysis, and financial reporting.

Technologies Used
Python: The main programming language used for the implementation.
Tesseract OCR: For optical character recognition from scanned images of bank statements.
OpenCV: For pre-processing and image manipulation.
Pandas: For data processing and manipulation.
NumPy: For numerical computations.
Matplotlib: For visualizing results.
scikit-learn: For any machine learning algorithms used in the project.
Features
OCR Extraction: Uses Tesseract to extract text from scanned or digital images of bank statements.
Data Preprocessing: Image processing techniques like resizing, thresholding, and noise removal to improve OCR accuracy.
Data Parsing: Parses the extracted text to identify relevant fields such as transaction descriptions, amounts, dates, and balances.
Data Classification: Classifies and organizes extracted data into structured formats such as CSV or JSON for further analysis.
Workflow
Image Preprocessing:

Images are preprocessed for optimal OCR extraction (e.g., resizing, thresholding).
Noise reduction techniques are applied to improve OCR accuracy.
OCR Extraction:

Text is extracted using Tesseract OCR.
Text Parsing and Data Extraction:

Regular expressions or string matching techniques are used to identify transaction data, balances, and other financial information.
Data Output:

The extracted data is saved in a structured format such as CSV or JSON.
Optionally, data is visualized for analysis.
