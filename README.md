# MNIST Classification with PyTorch: MLP vs LeNet

![MNIST Examples](https://upload.wikimedia.org/wikipedia/commons/2/27/MnistExamples.png)

A PyTorch implementation comparing Multi-Layer Perceptron (MLP) and LeNet architectures for handwritten digit recognition on the MNIST dataset.

## Project Overview
This project implements and compares two classic deep learning approaches for MNIST classification:
1. **Multi-Layer Perceptron (MLP)** with [256, 64, 16] hidden layers
2. **LeNet-5** convolutional neural network

## Key Features
### Implemented Functionality
- **Data Processing**
  - MNIST dataset loading and visualization
  - Custom train/test dataloaders
- **Model Architectures**
  - Configurable MLP with tanh activation
  - LeNet-5 CNN implementation
- **Training Pipeline**
  - Epoch training/validation loops
  - Accuracy calculation
  - Performance comparison
