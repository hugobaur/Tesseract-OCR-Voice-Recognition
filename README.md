# Tesseract-OCR-Voice-Recognition
Tesseract-OCR-Voice-Recognition


```from PIL import Image
import pytesseract
import argparse
import cv2
import os
import pyttsx3


1. Install tesseract using windows installer available at: https://github.com/UB-Mannheim/tesseract/wiki

2. Note the tesseract path from the installation.Default installation path at the time the time of this edit was: C:\Users\USER\AppData\Local\Tesseract-OCR. It may change so please check the installation path.

3. pip install pytesseract

4. set the tesseract path in the script before calling image_to_string:

pytesseract.pytesseract.tesseract_cmd = r'C:\Users\USER\AppData\Local\Tesseract-OCR\tesseract.exe