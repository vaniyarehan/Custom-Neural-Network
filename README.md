# California Housing Price Prediction Using Custom Neural Network

This project implements a feedforward neural network from scratch using **NumPy** to predict housing prices based on the California Housing Prices dataset.

---

## Project Overview

The goal is to predict median house values given features like location, median income, and housing age. This is a regression task solved using a custom-built neural network with:

- Two hidden layers
- Choice of **ReLU** or **Sigmoid** activation functions
- Batch gradient descent with mini-batches
- Early stopping based on mean squared error (MSE)
- Data preprocessing including normalization and one-hot encoding

---

## Features

- **Data Loading:** Loads and cleans the California housing dataset
- **Feature Engineering:** One-hot encodes categorical data, selects key features
- **Normalization:** Standardizes features and target variable
- **Neural Network Architecture:**
  - Input layer: 9 features
  - Two hidden layers: 4 neurons each
  - Output layer: 1 neuron (regression output)
- **User Input:** Choose activation function and training hyperparameters interactively
- **Training:** Mini-batch gradient descent with backpropagation
- **Evaluation:** Reports loss on training and test sets

---

## Requirements

- Python 3.6+
- NumPy
- Pandas

## Dataset

The data used is the California Housing Prices dataset from Kaggle:
https://www.kaggle.com/datasets/camnugent/california-housing-prices


## Notes

- This is an educational project aimed to understand the inner workings of neural networks.
- Performance can be improved by tuning hyperparameters or adding more layers.
- No advanced optimizers like Adam are implemented—only vanilla gradient descent.



