# CNN Computer Vision Prototype

## Project Overview

This project demonstrates a Convolutional Neural Network (CNN) based image classification system using TensorFlow and Keras.

The dataset contains synthetic images representing different surface conditions:
- normal
- scratch
- dent
- stain

The CNN model was trained to automatically classify images into these categories.

---

# Problem Type

This dataset represents an **Image Classification** problem because:
- Each image belongs to one category
- The objective is to predict the correct class label for an image

---

# Dataset Exploration

## Number of Classes
4 classes:
- normal
- scratch
- dent
- stain

## Dataset Information
- Total images: 480
- Image size: 96x96 pixels

---

# Image Preprocessing

The following preprocessing techniques were applied:

- Image resizing to 96x96
- Pixel normalization
- Training-validation split
- Batch processing using ImageDataGenerator

---

# CNN Concepts

## What is Convolution?

Convolution applies filters to images to detect patterns such as edges and textures.

## Why is Pooling Used?

Pooling reduces image size and computational complexity while preserving important features.

## Why is ReLU Used?

ReLU introduces non-linearity and helps CNNs learn complex image features efficiently.

## Why are CNNs Better for Images?

CNNs automatically learn spatial patterns and require fewer parameters than regular neural networks.

---

# Business Use Case

## Manufacturing Industry

This solution can help detect defects such as scratches, dents, and stains automatically during quality inspection.

Benefits:
- Faster inspection
- Reduced manual effort
- Improved product quality

---

# Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

# Repository Structure

part-2-cnn-computer-vision/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
├── sample_predictions/
└── results/