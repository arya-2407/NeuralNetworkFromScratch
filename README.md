Neural Network from Scratch
This repository contains an implementation of a simple neural network from scratch in Python, without using any deep learning libraries. The network is designed to classify data based on provided features using a single-layer neural network model with gradient descent optimization.

Dataset
The model is tested on the Heart Attack Analysis & Prediction Dataset, which includes features related to heart attack risk factors. The target variable (output) indicates whether a heart attack is likely.

Data Source: heart.csv
Features: Multiple health and demographic features.
Target: output (1 indicates heart attack, 0 indicates no heart attack)
Model Details
The neural network consists of:

A single hidden layer with a sigmoid activation function.
A loss function based on Mean Squared Error (MSE).
Training using gradient descent with manually calculated gradients.
Key Methods
Forward Propagation: Computes predictions based on the current weights and biases.
Backward Propagation: Calculates gradients of the loss with respect to weights and biases using the chain rule.
Optimizer: Updates weights and biases using the calculated gradients and a predefined learning rate.
