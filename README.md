# Multilayer Perceptron (MLP) for MNIST Digit Classification

## Assignment Overview
This project implements a Multilayer Perceptron (MLP) to classify handwritten digits from the MNIST dataset. The objective is to explore how the architecture of the MLP, particularly its depth, influences its performance in recognizing complex patterns in data.

## Dataset
The MNIST dataset consists of:
- **70,000 grayscale images** of handwritten digits (0-9).
- **60,000 training images** and **10,000 test images**.
- Each image has a resolution of **28x28 pixels**.

The dataset is readily available through Keras, facilitating easy loading and preprocessing.

## Model Architecture
The MLP model is structured as follows:
- **Input Layer**: Flattens the 28x28 pixel images into a 784-dimensional vector.
- **Hidden Layers**: 
  - First hidden layer with **128 neurons** using ReLU activation.
  - Second hidden layer with **64 neurons** using ReLU activation.
- **Output Layer**: Contains **10 neurons** (one for each digit) using the softmax activation function.

## Installation
To run this project, ensure you have Python installed along with the following libraries:
- NumPy
- Matplotlib
- Keras
- TensorFlow

You can install the required libraries using pip:
```bash
pip install numpy matplotlib keras tensorflow
