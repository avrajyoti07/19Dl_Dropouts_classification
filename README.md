# Dropouts Classification Neural Network Demo

A beginner-friendly deep learning project demonstrating binary classification using a Multilayer Perceptron (MLP) built with TensorFlow/Keras. This repository serves as a starter-phase template for understanding neural network architectures, training metrics, and visualizing decision boundaries.

## Overview
This project builds a simple binary classification model on a 2D synthetic dataset. It is designed for deep learning beginners to understand how a model learns over time and how to visualize its actual decision-making process. While the `Dropout` layer is imported, the current base model runs without it, providing a perfect starting point to experiment by adding dropout layers and observing how regularization affects the validation metrics and decision boundaries. 

## Features
* **Custom Dataset**: A 2D non-linear dataset visualized using `matplotlib`.
* **Keras Sequential API**: A baseline deep learning model using `Dense` layers, `relu` activations, and a `sigmoid` output.
* **Performance Tracking**: Plots training vs. validation loss and accuracy over 500 epochs to help identify overfitting.
* **Decision Boundary Visualization**: Integrates `mlxtend` via a custom `KerasClassifierWrapper` to beautifully plot the model's decision regions.

## Prerequisites
Ensure you have Python installed along with the following libraries:
* `numpy`
* `matplotlib`
* `tensorflow` (or `keras`)
* `mlxtend`
* `scikit-learn` (required by mlxtend)

You can update or install the specific visualization tool using:
```bash
pip install --upgrade mlxtend
