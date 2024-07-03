# OCR Project using Pytesseract

This project demonstrates the use of Optical Character Recognition (OCR) to extract text from images using Python libraries like Pytesseract, Pillow, and OpenCV.

## Prerequisites

Before running the script, make sure you have the following installed:
- Python 3
- PIL (Pillow)
- OpenCV (cv2)
- pytesseract
- Tesseract-OCR engine

## Installation

1. **Install Python Libraries**: You can install the required Python libraries using pip:

 
pip install Pillow pytesseract opencv-python

Running the Script
Prepare Your Environment:

Upload your target OCR image to the directory where you're running the script, or note the path of your image.
If using an environment like Google Colab, make sure to upload the image there.
Run the Script:

Update the image_path in the script to the location of your image file.
Execute the script either through a Python environment or an IDE that supports Python.
Script Overview
The script performs the following operations:

Loads an image specified by image_path.
Converts the image to grayscale using OpenCV for better processing.
Applies binary threshold inversion to enhance the text in the image.
Uses Pytesseract to perform OCR on the preprocessed image.
Outputs the extracted text.
Additional Notes
The accuracy of OCR can vary based on the quality and complexity of the input image. Adjust preprocessing steps as necessary to improve results.
If you encounter issues with Tesseract not recognizing text as expected, consider custom configurations or additional preprocessing.
License
This project is open-source and available under the MIT License.
