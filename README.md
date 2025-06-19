# 🖼️ Image to Text Extractor

This Python script uses OpenCV and Tesseract OCR to extract text from images. It preprocesses the image, identifies text blocks using contour detection, and applies OCR to extract readable text.

---

## 🚀 Features

- Convert images to text using Tesseract OCR
- Preprocesses image using OpenCV (grayscale, threshold, dilation)
- Detects text blocks and extracts text
- Saves the output in a `recognized.txt` file

---

## 🛠️ Requirements

- Python 3.x
- OpenCV
- Pytesseract
- Tesseract-OCR installed

---

## 🔧 Installation (if you running this on your machine )

step 1 :
```bash
pip install opencv-python pytesseract
```
step 2 :
```bash
python image_to_text.py


