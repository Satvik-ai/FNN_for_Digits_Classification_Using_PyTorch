# Feedforward Neural Network for Digits Classification Using PyTorch

This project demonstrates how to build and train a simple feedforward neural network using PyTorch for classifying handwritten digits from the popular MNIST dataset.

## Project Overview

The goal of this project is to:
- Understand the basics of building neural networks using PyTorch.
- Perform digit classification using a fully connected feedforward neural network.
- Train and evaluate the model performance using accuracy metrics.

## Features

- Load and preprocess MNIST dataset.
- Construct a multi-layer feedforward neural network using.
- Train the model using adam and cross-entropy loss.
- Evaluate model accuracy on the test set.
- Confusion matrix for more detailed evaluation.

## Technologies Used

- Python 3
- PyTorch
- Matplotlib
- Torchvision (for loading MNIST)

## Dataset

The project uses the [MNIST dataset](http://yann.lecun.com/exdb/mnist/), which is a large database of handwritten digits commonly used for training various image processing systems. It contains:

- 60,000 training images
- 10,000 testing images
- Images are grayscale and sized 28x28 pixels
- Each image represents a digit from 0 to 9

The dataset is automatically downloaded using the `torchvision.datasets.MNIST` class.

## Model

- Input Layer (784 features)
- Hidden Layer with Relu activation function
- Output Layer (10 neurons)

## Training
- Uses a loss function like CrossEntropyLoss
- Optimized using Adam optimizer
- Training loop with backpropagation

## Results

- Achieved high accuracy (97.15%) on MNIST test data.
