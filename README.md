# MNIST Neural Network From Scratch (NumPy)

This project implements a fully-connected neural network from scratch using only NumPy.
It trains on the MNIST digit dataset and achieves 97–98% accuracy using mini-batch
gradient descent. The entire forward and backward propagation is manually coded
without PyTorch or TensorFlow.

## Features
- 2-layer neural network (784 → 256 → 10)
- ReLU activation + Softmax output
- Cross-entropy loss
- Mini-batch gradient descent (batch_size = 64)
- Train/Dev split
- Parameter initialization (He init)
- Accuracy ~98% on MNIST (dev set)
