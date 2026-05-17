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

# CNN Model Architecture

The CNN model includes:

- Convolutional layers
- ReLU activation function
- MaxPooling layers
- Flatten layer
- Dense fully connected layers
- Softmax output layer

---

# Model Performance

The CNN model achieved good classification performance on the synthetic image dataset.

Outputs generated:
- Accuracy and validation curves
- Confusion matrix
- Sample predictions

---

# CNN Concepts

## What is Convolution?

Convolution applies filters to images to detect important patterns such as edges, textures, and shapes.

## Why is Pooling Used?

Pooling reduces image dimensions and computational complexity while preserving important image features.

## Why is ReLU Commonly Used?

ReLU helps the neural network learn non-linear patterns efficiently and improves training performance.

## Why are CNNs Better for Images?

CNNs automatically learn spatial features from images and require fewer parameters than traditional neural networks.

---

# Business Use Case

## Manufacturing Industry

This solution can help automate quality inspection in manufacturing by detecting defects such as:
- scratches
- dents
- stains

Benefits include:
- Faster inspection
- Reduced manual effort
- Improved product quality
- Lower operational costs

---

# Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow

---

# Repository Structure

part-2-cnn-computer-vision/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
├── accuracy_loss_curves.png
├── confusion_matrix.png
├── prediction_outputs.png
