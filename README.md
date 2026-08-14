# Handwritten Digits Classification

Classifying handwritten digit images from 0 to 9 using machine learning and neural networks.

## Overview

This project uses the MNIST dataset to classify handwritten digit images into 10 classes.

The project compares classical machine learning models with a dense neural network and a convolutional neural network to see which approach works best for image classification.

## Dataset

The dataset contains:

- 60,000 training images
- 10,000 test images
- 10 digit classes from 0 to 9
- 28 × 28 grayscale images

The standard MNIST train and test split was used.

## Problem

The main questions were:

1. What does the dataset look like?
2. Can a model correctly classify handwritten digits?
3. Which model performs best on the test data?

## Approach

```text
MNIST Data
    ↓
Data Loading
    ↓
Exploratory Analysis
    ↓
Image Normalization
    ↓
Classical ML Models
    ↓
Dense Neural Network
    ↓
CNN
    ↓
Model Comparison
    ↓
Error Analysis
