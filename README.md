# MNIST Digit Classification: Perceptron vs ANN vs CNN

## Problem Statement

Handwritten digit recognition is a classic computer vision problem where the goal is to correctly classify grayscale images of digits (0–9) from the MNIST dataset. This project compares three neural network architectures — a simple Perceptron, a deeper Artificial Neural Network (ANN), and a Convolutional Neural Network (CNN) — to evaluate how model complexity impacts classification accuracy on image data.

## Overview

-- Loaded and preprocessed the MNIST dataset (60,000 train / 10,000 test images)
-- Normalized pixel values and one-hot encoded labels
-- Built and trained three models of increasing complexity:
  -- **Perceptron** – single dense layer with softmax

- **ANN** – multiple dense hidden layers
  -- **CNN** – convolutional + pooling layers for spatial feature extraction
- Evaluated each model using accuracy, confusion matrices, and training/validation curves
- Compared final performance across all three architectures

## Tech Stack

- Python, NumPy, Pandas
- TensorFlow / Keras
- Matplotlib, Seaborn (visualizations)
- Scikit-learn (metrics)

## Results

The CNN outperformed both the Perceptron and ANN, confirming that convolutional layers are better suited for capturing spatial patterns in image data compared to fully connected architectures.

# MNIST-Digit-Classification-Perceptron-vs-ANN-vs-CNN
# MNIST-Digit-Classification-Perceptron-vs-ANN-vs-CNN
