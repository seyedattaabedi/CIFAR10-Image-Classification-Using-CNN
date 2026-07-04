# CIFAR-10 Image Classification Using CNN

This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images from the CIFAR-10 dataset.

## Dataset

The CIFAR-10 dataset contains 60,000 color images (32×32 pixels) divided into 10 object categories:

* Airplane
* Automobile
* Bird
* Cat
* Deer
* Dog
* Frog
* Horse
* Ship
* Truck

## Technologies Used

* Python
* TensorFlow / Keras
* OpenCV
* NumPy
* Matplotlib

## Model Architecture

* Conv2D (32 filters, ReLU)
* MaxPooling2D
* Conv2D (64 filters, ReLU)
* MaxPooling2D
* Conv2D (64 filters, ReLU)
* Flatten Layer
* Dense Layer (64 neurons)
* Output Layer (10 classes)

## Workflow

1. Load and preprocess CIFAR-10 dataset
2. Normalize image values
3. Build and train CNN model
4. Evaluate performance
5. Predict object classes on custom images
6. Save and reload trained model

## Results

* Training Accuracy: ~80%
* Validation Accuracy: ~71%

## Goal

The main goal of this project is to gain practical experience in computer vision and image classification using convolutional neural networks.
