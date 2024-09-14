## Libraries Used

The following Python libraries are required to run the code:

- **NumPy**: For array manipulation and efficient numerical computations.
- **Matplotlib**: For plotting and visualizing data (used for loss visualization and more).
- **Jupyter Notebook**: For running the notebooks interactively.
- Please see import statements for other necessary libraries.

# Neural Network Framework: Backpropagation Implementation

## Overview

This repository contains an implementation of a custom neural network framework with a focus on backpropagation. The code is designed to help you understand the core principles of training neural networks, including how gradients are calculated and how they are used to update the network's weights.

The implementation is modular, allowing for easy modification and extension, and it is written entirely from scratch using Python and Jupyter notebooks.

## Contents

1. **Backpropagation.ipynb**
    - This notebook demonstrates the core implementation of the backpropagation algorithm.
    - It explains how gradients are computed for a simple neural network and shows how they are used to update the weights during training.
    - Example training runs are included, allowing you to visualize how weight updates affect the loss function over time.

2. **Neural_Network_Framework.ipynb**
    - This notebook contains a custom-built framework for constructing and training neural networks.
    - The framework is modular, allowing you to easily add layers, activation functions, and loss functions.
    - It demonstrates how to set up and train a feedforward neural network using backpropagation.

## Key Concepts

- **Backpropagation**: The algorithm used to compute gradients of the loss function with respect to network weights, enabling efficient weight updates during training.
- **Gradient Descent**: An optimization technique used to adjust the weights of the neural network in order to minimize the loss function.
- **Feedforward Neural Network**: A type of neural network where data flows in one direction, from input to output, without any cycles or feedback loops.


## Usage

1. Clone the repository:

```bash
git clone https://github.com/Marwan-Alhindi/Custom-Neural-Network-Framework-with-Backpropagation.git
cd Custom-Neural-Network-Framework-with-Backpropagation
```

2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open either `backpropagation.ipynb` or `neural_network_framework.ipynb` to explore the implementations.
