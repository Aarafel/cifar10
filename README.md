CIFAR-10 Image Classification
This project demonstrates image classification using the CIFAR-10 dataset with a feedforward neural network.

Overview
Load Data: Uses CIFAR-10 dataset for training and testing.

Visualize Data: Displays sample images and class distribution.

Preprocess Data: Flattens, normalizes images, and one-hot encodes labels.

Flatten Images: Converts the 32x32x3 images into 1D vectors.

Normalize: Scales pixel values to the range [0, 1].

One-Hot Encoding: Converts class labels into one-hot encoded vectors.


Model: Defines a feedforward neural network with layers: 512-256-128.

A simple feedforward neural network is created with the following architecture:

Input layer: 512 units
Hidden layer 1: 256 units
Hidden layer 2: 128 units
Output layer: 10 units (one for each class)

Train & Evaluate: Trains the model and plots accuracy/loss curves.

Predict: Makes predictions on random test images.
