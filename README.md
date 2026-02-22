# From-Scratch Neural Network
(Originally developed, trained and tested on kaggle: kaggle.com/code/spandanjawkhedkar/neural-network-from-scratch )

A manual implementation of a multi-layer neural network built entirely without high-level machine learning libraries (like TensorFlow or PyTorch). 

This project tracks the iterative development of low-level AI architecture, specifically focusing on manually coding forward propagation, the backpropagation chain rule, and cost-driven weight updates.

# Project Evolution

01_base_logic.ipynb: 
A baseline perceptron model mapping raw inputs directly to outputs.

02_hidden_layer_convergence.ipynb: 
Introduced a 5-node hidden layer. Successfully optimized the manual backpropagation calculus, achieving convergence (Cost: 0.00009) and 99.0% accuracy on the test set.

03_vanishing_gradient.ipynb: 
Expanded the architecture to two hidden layers (7x7). The mathematical chain rule is fully implemented for deep backpropagation. However, accuracy plateaus at 64%, effectively demonstrating the **Vanishing Gradient Problem** associated with using Sigmoid activation functions in deeper unoptimized networks.
