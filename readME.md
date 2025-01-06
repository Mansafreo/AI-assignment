# MNIST Digit Recognition with Neural Network

## Introduction

This notebook demonstrates the creation and training of a neural network to recognize handwritten digits from the MNIST dataset. The goal is to achieve an accuracy of over 95% on the test data and ensure the model can recognize at least 4 digits accurately.

## Problem Overview

The MNIST dataset consists of 60,000 training images and 10,000 testing images of handwritten digits (0-9). Each image is 28x28 pixels in grayscale. The task is to build a neural network that can accurately classify these images.

## Technical Overview

The neural network consists of:
1. **Input Layer**: Accepts a 784-dimensional vector (28x28 pixels).
2. **Hidden Layer**: Uses ReLU activation function.
3. **Output Layer**: 10 neurons with SoftMax activation function to output probabilities for each digit.

## Steps

### 1. Preparing Data
- Load the MNIST dataset from IDX files.
- Normalize the image data.
- One-hot encode the labels.

### 2. Defining the Neural Network
- Implement a neural network class with methods for forward pass, backward pass, and training.
- Use ReLU activation for the hidden layer and SoftMax for the output layer.

### 3. Training and Evaluation
- Train the neural network on the training data.
- Evaluate the model on the test data.
- Calculate and display the accuracy and confusion matrix.

### 4. Secondary Evaluation
- Calculate accuracy for each digit.
- Display sample images and their corresponding accuracies.

## Results
- The model achieved an accuracy of over 97% on the test data.
- The accuracy for each digit was evaluated and displayed.

## Conclusion
The neural network successfully recognized handwritten digits from the MNIST dataset with high accuracy, demonstrating its robustness and effectiveness.

## Dependencies
- numpy
- matplotlib
- tabulate
- seaborn

## Usage
To run this notebook, ensure you have the required libraries installed. You can install them using:
```sh
pip install numpy matplotlib tabulate seaborn
```

Run the notebook to see the step-by-step implementation and results.