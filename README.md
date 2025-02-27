Micrograd (The spelled out intro into neural network and backpropagation)

A lightweight, educational implementation of a neural network autograd engine, inspired by Andrej Karpathy's Micrograd tutorial. This project demonstrates the fundamentals of backpropagation and automatic differentiation in a simple, from-scratch Python library.

Overview

Micrograd is a tiny autograd engine that builds a computational graph to compute gradients automatically via backpropagation. It’s designed for learning purposes, breaking down how modern deep learning frameworks (like PyTorch or TensorFlow) work under the hood. This implementation supports basic scalar operations and can train small neural networks.

Features

Automatic Differentiation: Computes gradients of arbitrary scalar-valued functions using reverse-mode autodiff (backpropagation).
Scalar Operations: Supports addition, multiplication, exponentiation, and more.
Neural Network Building Blocks: Includes neurons, layers, and a simple MLP (Multi-Layer Perceptron) implementation.
Educational Focus: Clean, minimal code with comments for understanding the mechanics of backpropagation.
