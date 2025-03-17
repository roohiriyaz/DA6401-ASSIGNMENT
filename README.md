DA6401 Assignment - Feedforward Neural Network

Description
This repository contains an implementation of a **Feedforward Neural Network** (FNN) for classifying images from the **Fashion-MNIST dataset**. The model is implemented using **NumPy** and supports multiple optimization algorithms.

Features
- Flexible number of hidden layers and neurons per layer.
- Implements backpropagation with multiple optimizers:
  - Stochastic Gradient Descent (SGD)
  - Momentum-based Gradient Descent
  - Nesterov Accelerated Gradient Descent
  - RMSprop
  - Adam
- Supports **batch training** and integrates with **Weights & Biases (wandb)** for experiment tracking.
- Two loss functions available: **Cross-Entropy Loss & Mean Squared Error (MSE)**.
