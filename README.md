# Handwritten Digit Classification using Convolutional Neural Networks (CNN)

## Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images from the MNIST dataset. The MNIST dataset contains handwritten digits, which are widely used for training various image processing systems.

## Features

- **Data Loading**: Utilizes TensorFlow's dataset utilities to load and preprocess the MNIST dataset.
- **Model Architecture**: Constructs a CNN model using Keras' Sequential API.
- **Training**: Trains the model with training data and validates it using test data.
- **Evaluation**: Evaluates the model's performance and accuracy on the test dataset.
- **Visualization**: Provides visualization of training history and sample predictions.

## Model Architecture
The CNN model consists of the following layers:

- Convolutional layers with ReLU activation
- MaxPooling layers
- Fully connected (Dense) layers
- Dropout layers to prevent overfitting
## Results
![image](https://github.com/user-attachments/assets/a845ff4a-32e7-4c57-9b92-b0218134b4ff)


## Installation

To run this project, you will need to have Python and the following packages installed:

- TensorFlow
- Keras
- NumPy
- Matplotlib

You can install the required packages using:

```bash
pip install tensorflow keras numpy matplotlib
