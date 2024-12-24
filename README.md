# TF-MNIST-Image-Classification

Welcome to the **TensorFlow MNIST Image Classification** repository! This project demonstrates how to build, train, and evaluate a neural network for classifying handwritten digits using TensorFlow and the MNIST dataset.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Evaluation](#evaluation)
- [Predictions](#predictions)
- [Results](#results)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction

This project aims to create and train a neural network model that takes an image of a handwritten digit as input and predicts the class of that digit (0-9). Using TensorFlow and Keras, we preprocess the MNIST dataset, build a neural network with multiple layers, and achieve high accuracy in digit classification.

![Hand Written Digits Classification](images/1_1.png)

## Features

- **Data Preprocessing:** Reshape and normalize image data for optimal model performance.
- **One-Hot Encoding:** Convert categorical labels into a format suitable for classification.
- **Neural Network Architecture:** Build a sequential model with multiple dense layers and activation functions.
- **Training & Evaluation:** Train the model on the training set and evaluate its performance on the test set.
- **Predictions Visualization:** Visualize model predictions against true labels.

## Dataset

We use the [MNIST dataset](http://yann.lecun.com/exdb/mnist/) which consists of 70,000 grayscale images of handwritten digits (0-9). The dataset is split into 60,000 training images and 10,000 testing images.

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/your-username/TensorFlow-MNIST-Image-Classification.git
   cd TensorFlow-MNIST-Image-Classification
