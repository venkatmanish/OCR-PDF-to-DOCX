#OCR-PDF-to-DOCX
OCR-PDF-to-DOCX is a Python project that allows you to extract paragraphs from PDF files using Optical Character Recognition (OCR) technology and generate a DOCX file while preserving the original formatting. It leverages popular libraries such as pytesseract, pdf2image, and python-docx to perform the conversion seamlessly.

Features
Extracts paragraphs from a PDF file using OCR.
Supports different types of lists (numbered, alphabets, bullets).
Preserves the formatting and structure of the original PDF content.
Process annotation JSON files to extract relevant paragraph information.
Generates a DOCX file with the extracted paragraphs.
How to Use
Install the required dependencies: json, pytesseract, pdf2image, python-docx.
Clone this repository or download the project files.
Ensure that you have a PDF file and its corresponding annotation JSON file.
Replace the paths in the code with the paths to your PDF file, annotation JSON file, and desired output file.
Run the script and wait for the execution to complete.
The result will be saved in the specified output file as a JSON format, containing the extracted paragraphs and their associated information.
You can open the generated DOCX file to view the extracted paragraphs with preserved formatting.
Feel free to customize and modify the code to suit your specific needs. You can also explore additional functionalities and enhancements to extend the project further.
