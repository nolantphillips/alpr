Automated License Plate Recognition (ALPR) System
=================================================

This project is an end-to-end Automated License Plate Recognition (ALPR) system using YOLOv12 for object detection and Tesseract-OCR for optical character recognition.

Overview
--------
The system performs two main tasks:
1. **Vehicle and License Plate Detection**: Using YOLOv12 to detect vehicles and locate license plates in real-time video or image input.
2. **Character Recognition**: Using Tesseract-OCR to extract and read the license plate numbers from the detected regions.

Project Structure
-----------------
- /models/
  Contains the YOLOv12 weights and config files.

- /data/
  Input images or videos for processing.

- /runs/
  Model runs.

- CSE574_Team6_code.ipynb
  Main notebook that integrates detection and OCR.

-datasets.yaml
  File that directs YOLOv12 to the dataset for training of model.

-requirements.txt
  Python packages used for development.
  
Requirements
------------
- Python 3.8+
- OpenCV
- PyTorch
- Tesseract-OCR (system installation required)
- pytesseract
- numpy
- yolov12 (custom implementation or clone from relevant repository)
