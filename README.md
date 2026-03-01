->Neural Network Binary Classification 
Overview

This Jupyter Notebook demonstrates how artificial neural networks can be used to solve a binary classification problem using PyTorch. The project focuses on classifying data points arranged in circular patterns  a classic example of a non-linear machine learning problem.

The notebook walks through the complete deep learning workflow, starting from data preparation and visualization to model training, evaluation, and comparison of different neural network architectures.

->Project Goal

The main objective is to understand:

How neural networks learn patterns from data

Why activation functions are necessary

How model complexity affects performance

Differences between optimization algorithms

How decision boundaries change across models

->How the Notebook Works

The notebook follows a structured machine learning pipeline:

1. Data Preparation

Loads a synthetic circles dataset.

Inspects and prepares features for training.

Ensures correct data formats and types.

2. Data Visualization

Plots the dataset to show its circular structure.

Helps understand why a linear model cannot solve the problem.

3. Train–Test Split

Divides data into training and testing sets to evaluate generalization.

4. Environment Setup

Configures computation device (CPU/GPU).

Sets tensor data types for PyTorch operations.

5. Model Development

Multiple neural network models are implemented:

ModelV0 – Simple architecture with limited capacity

ModelV1 – Larger network but without activation functions

ModelV2 – Deep network with ReLU activation functions

Each model is designed to highlight how architecture choices impact learning.

6. Training Process

Defines loss function and optimizers.

Runs training loops over multiple epochs.

Tracks accuracy and loss during learning.

7. Model Evaluation

Compares training and testing performance.

Visualizes decision boundaries learned by each model.

8. Optimizer Comparison

An additional experiment compares:

SGD optimizer

Adam optimizer

This shows how optimization strategies influence convergence speed.

-> Key Learning Concepts

This notebook demonstrates several important deep learning ideas:

Linear models cannot solve non-linear problems.

Activation functions enable neural networks to learn complex patterns.

Increasing parameters alone does not guarantee better performance.

Proper optimization improves training efficiency.

Visualization helps diagnose model behavior.

-> Results Summary

Models without activation functions perform poorly on circular data.

Networks using ReLU learn curved decision boundaries effectively.

The deeper model achieves high accuracy on both training and test sets.

Adam optimizer generally converges faster than SGD.

->Technologies Used

Python

PyTorch

NumPy

Matplotlib

Jupyter Notebook
