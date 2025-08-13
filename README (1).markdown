# MNIST Image Classification with PyTorch and TensorFlow

## Overview

This project implements image classification on the MNIST dataset, which consists of 28x28 grayscale images of handwritten digits (0-9). The goal is to train neural networks to classify digits accurately using **PyTorch** and **TensorFlow**. The project achieves:

- **PyTorch**: 96.87% test accuracy
- **TensorFlow**: 97.54% test accuracy

The code is beginner-friendly, developed in a Kaggle Notebook, and includes data loading, model training, evaluation, and visualizations (loss curves, predictions, and confusion matrix).

## Technologies Used

- **Kaggle Notebook**
- **PyTorch** & **TensorFlow/Keras**
- **Matplotlib & Numpy**

## Key Results

- **PyTorch Model**:
  - Training Loss: 0.0969 (Epoch 5)
  - Test Accuracy: 96.87%
- **TensorFlow Model**:
  - Training Loss: 0.0467 (Epoch 5)
  - Validation Loss: 0.0927
  - Test Accuracy: 97.54%

## Recommendations:

- Add dropout to reduce overfitting.
- Implement a convolutional neural network (CNN) for higher accuracy (e.g., 99%+).
- Experiment with hyperparameters (epochs, learning rate, batch size).