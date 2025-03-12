# Rudimentary Neural Network from Scratch

## Introduction & Motivation

This project implements a neural network from scratch using only Python and NumPy. The motivation behind this project was to gain a deeper understanding of how machine learning algorithms work by building one from the ground up. By coding every integral part, from weighted sums in neurons to backpropagation, a solid understanding of linear algebra and optimization techniques was developed.

Creating the network from scratch demonstrates the ability to take theoretical mathematical concepts and apply them as efficient, functional code. This project reflects a commitment to lifelong learning and a passion for innovation. It represents the challenges faced in real-world applications where developing scalable, interpretable models is of utmost importance. 

## Helper Functions

The project includes helper functions for activation functions (ReLU, softmax), their derivatives, and the cross-entropy loss function. These functions are essential for the forward and backward passes of the neural network.

## Build the Neural Network Class

The core of the project is the `NeuralNetwork` class, which encapsulates the structure and functionality of the neural network. It includes methods for:

- `__init__`: Initializes the network's weights and biases using He initialization.
- `forward`: Performs the forward pass, calculating the output of the network.
- `backward`: Performs the backward pass (backpropagation), updating the weights and biases based on the error.
- `train`: Trains the network over a specified number of epochs.

## Testing the Network

The neural network is tested on two datasets:

1. **XOR Dataset:** A simple dataset to verify the network's ability to learn non-linear patterns.
2. **Synthetic Dataset:** A synthetic dataset with three classes to evaluate the network's performance on a more complex task.

## Observations and Results

- **XOR Dataset:** The network successfully learns the XOR function, achieving 100% accuracy after training.
- **Synthetic Dataset:** The network achieves high accuracy on the synthetic dataset, demonstrating its ability to generalize to new data.

- **Further Exploration:** The project can be extended by testing the network on real-world datasets like MNIST or CIFAR-10.

## Conclusion

This project successfully implemented a neural network from scratch, providing valuable insights into the inner workings of machine learning algorithms. The results demonstrate the network's ability to learn and generalize, highlighting its potential for solving real-world problems.
