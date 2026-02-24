# MNIST-Handwritten-Digit-Classification-ANN-
This project implements a classic Artificial Neural Network (ANN) to recognize and classify handwritten digits from the MNIST dataset. It uses the TensorFlow/Keras library to achieve high accuracy through a multi-layer perceptron (MLP) architecture.

## Overview
The goal of this project is to take a **28x28** pixel image of a handwritten digit (0–9) and correctly predict its value. This is a fundamental "Hello World" project in Deep Learning.

### Key Features:
*   **Data Normalization:** Scales pixel values from [0, 255] to [0, 1] for faster convergence.
*   **One-Hot Encoding:** Converts integer labels into categorical vectors.
*   **Multi-Layer Architecture:** Uses dense layers with ReLU activation and a Softmax output layer.
*   **Optimization:** Utilizes the Adam optimizer for efficient weight updates.


##  Model Architecture
The model is a Sequential Artificial Neural Network consisting of the following layers:

| Layer | Type | Neurons | Activation |
| :--- | :--- | :--- | :--- |
| **Input** | Flatten | 784 | N/A |
| **Hidden 1** | Dense | 50 | ReLU |
| **Hidden 2** | Dense | 30 | ReLU |
| **Output** | Dense | 10 | Softmax |



## Installation & Usage

### Prerequisites
Ensure you have Python 3.x installed along with the following libraries:
```bash
pip install tensorflow numpy
