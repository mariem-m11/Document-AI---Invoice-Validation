
# Automated Invoice Validation System

## Overview

This project focuses on developing an AI-driven system that automates the validation of financial invoices. The system leverages **Machine Learning (ML)** and **Deep Learning (DL)** techniques, including **Optical Character Recognition (OCR)** and **Document Layout Analysis**, to detect and validate key elements in invoices such as the presence of stamps, signatures, and specific fields. The system also handles various invoice formats, including handwritten and machine-printed ones.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data](#data)
- [Results](#results)
- [Contributors](#contributors)
- [Acknowledgments](#acknowledgments)

## Features
- Automatic validation of invoices by extracting key information.
- Handles scanned machine-written invoices with poor quality or uneven lighting.
- Utilizes **OCR** to convert image-based text into structured data.
- Preprocessing techniques for improving image quality and OCR results.
- **Deep Learning** models benchmarked and optimized for:
  - Document Layout Analysis
  - Signature and Stamp Detection
  - Token Recognition
- Tracks and manages experiments using **MLflow** and **DagsHub**.
  
## Technologies
The key technologies and libraries used in this project include:
- **Python**: Core programming language.
- **PyTorch**: For deep learning models and training pipelines.
- **MLflow**: For tracking ML experiments and performance metrics.
- **DagsHub**: For data versioning and centralized metric collection.
- **Pytesseract** & **Azure OCR**: For optical character recognition.
- **RetinaNet**, **Faster R-CNN**, **FCOS**, and **SSD**: For signature and stamp detection.

## Results
- **Document Layout Analysis**: The best model was LayoutLMv3.
- **Signature and Stamp Detection**: **RetinaNet** outperformed other object detection models.
- **OCR Performance**: Azure OCR provided higher precision and recall than Pytesseract for token extraction tasks.

