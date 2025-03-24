# Handwritten-Digit-Recognition-HDR-

Overview

Handwritten Digit Recognition (HDR) is a deep learning project that uses a Convolutional Neural Network (CNN) to classify handwritten digits from images. The model is trained on the MNIST dataset and achieves high accuracy in digit recognition.

Technologies Used

Python

TensorFlow

OpenCV

NumPy

Flask (for deployment)

Features

CNN-based digit classification with 98%+ accuracy

Data preprocessing using OpenCV and NumPy

Model trained on 60,000 images from the MNIST dataset

Real-time digit classification through a Flask API

Supports image augmentation for improved model generalization

Installation

pip install tensorflow opencv-python numpy flask

Usage

Run the Flask server:

python app.py

Send a POST request with an image to classify the digit.
