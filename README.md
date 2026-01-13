Neural Networks and Deep Learning — Chapter 1 (Michael Nielsen)

This repository contains my solutions and exercises for Chapter 1 of Neural Networks and Deep Learning by Michael Nielsen: Using neural nets to recognize handwritten digits. The chapter explores the fundamentals of neural networks, how they learn, and how to implement them from scratch.

 Overview

Chapter 1 provides a practical and intuitive introduction to neural networks using the handwritten digit recognition problem (MNIST) as the working example. The key ideas covered include:

Perceptrons vs. Sigmoid Neurons
Perceptrons are simple binary-output units. Sigmoid neurons extend this idea with a smooth activation function that allows small changes in weights and biases to produce small changes in output — a critical property for learning.

Neural Network Intuition
Instead of writing explicit rules, neural networks automatically learn patterns from data by adjusting parameters. The chapter demonstrates this with a small neural network capable of recognizing handwritten digits.

Stochastic Gradient Descent (SGD)
SGD is introduced as the core algorithm for training neural networks: it repeatedly updates weights and biases in the direction that minimizes the cost (error) — essentially moving opposite to the cost gradient.

MNIST Implementation
A short (~74-line) Python implementation that trains a network on MNIST and achieves high accuracy, demonstrating how a learning algorithm can be built from scratch without high-level libraries.
