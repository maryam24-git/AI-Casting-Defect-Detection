# AI-Casting-Defect-Detection
AI-powered machine vision system for automated casting defect detection using CNNs, OpenCV, and TensorFlow.

## Overview
-This project presents an AI-powered machine vision system for automated industrial quality inspection using deep learning and computer vision techniques.
- The system is designed to identify defective and non-defective casting products using grayscale image analysis, preprocessing, convolutional neural networks (CNNs), and evaluation techniques.
- The project was developed as part of an industrial AI inspection laboratory focused on smart factory automation.

# Objectives

- Perform industrial image preprocessing.
- Extract important visual features.
- Build an AI-based defect detection model.
- Evaluate inspection system performance.
- Simulate real-time industrial inspection tasks.

# Technologies Used

- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

# Dataset

Casting Product Defect Dataset

Dataset contains:
- OK Products
- Defective Products

# Part A - Image Acquisition & Preprocessing

Implemented Features:

- Image importing
- Image resizing and normalization
- Gaussian filtering
- CLAHE contrast enhancement
- Edge detection using Canny
- Histogram analysis
- Morphological operations
- Otsu threshold segmentation

Techniques Used:
- Edge Detection
- Histogram Analysis
- Morphological Processing

# Part B - AI-Based Inspection System

Implemented Approach:
- Binary Classification

Model Used:
- Convolutional Neural Network (CNN)

CNN Architecture:
- Conv2D Layers
- MaxPooling Layers
- Dense Layers
- Dropout Layer
- Sigmoid Output Layer

Capabilities:
- Detect defective products
- Detect non-defective products
- Predict unseen industrial images

# Part C - System Evaluation

Evaluation Metrics:
- Classification Accuracy
- False Positives
- False Negatives
- Precision
- Recall
- F1-Score

Additional Experiments:
- Processing speed analysis
- Lighting sensitivity testing
- Noise robustness testing
- AI vs traditional inspection comparison

# Part D - Extension Challenges

Implemented Extensions:
- Real-time inspection simulation
- Conveyor belt simulation
- TensorFlow Lite edge deployment
- Defect localization using bounding boxes
- Human-machine interface dashboard

# Results

- The CNN-based inspection system achieved high classification accuracy and demonstrated robustness under varying industrial conditions.
- The system successfully simulated industrial quality inspection workflows.
