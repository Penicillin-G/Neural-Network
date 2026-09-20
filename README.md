# Neural-Network

## Overview

A beginner-friendly implementation of a neural network built from scratch using Python and NumPy, without deep learning frameworks such as TensorFlow or PyTorch.

The project explores the fundamental mathematics behind neural networks through a simple binary classification task: learning the logic gate functions.

## Objectives
* Understand how artificial neurons process inputs.
* Implement forward propagation and sigmoid activation.
* Calculate prediction error using binary cross-entropy.
* Implement backpropagation and gradient descent.
* Train a model using an iterative training loop.
* Track and visualize training loss.
* Organize the network into a reusable Python class.

## Technologies Used
* Python
* NumPy

## Project Structure

```text
neural-network-from-scratch/
│
├── neural_network.py
├── not_logic_gate.py
├── and_logic_gate.py
├── README.md
```

## Logic Gate Implementations

The project explores neural network learning through three fundamental logic gates:

| Logic Gate | Description                                      |
| ---------- | ------------------------------------------------ |
| OR         | Learns to output 1 when at least one input is 1. |
| NOT        | Learns to invert a single binary input.          |
| AND        | Learns to output 1 only when both inputs are 1.  |

Each implementation provides an opportunity to explore how weights, biases, activation functions, and gradient-based learning influence a model's predictions.

## Usage

Run each implementation separately:

```bash
python neural_network.py
python not_logic_gate.py
python and_logic_gate.py
```

Ensure that the required dependencies are installed before running the scripts.

## Learning Outcomes

Through this project, I am developing a practical understanding of neural network fundamentals, including how model parameters are initialized, how errors propagate backward, and how gradient descent adjusts weights and biases during training.

## Future Improvements

* Extend the implementations to support multiple neurons and hidden layers.
* Experiment with different activation and loss functions.
* Compare the learning behavior of different logic gates.
* Implement XOR classification using a multilayer neural network.
* Explore more complex datasets and classification tasks.
