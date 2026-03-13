# Plant Image Classification

This project focuses on classifying plant species from images using deep learning. I implemented and compared two approaches: a custom Convolutional Neural Network (CNN) and a transfer learning model based on ResNet18.

## Project Overview

The goal of this project was to build an image classification pipeline for plant recognition and evaluate how a baseline CNN compares to a pretrained deep learning architecture.

The workflow includes:
- image preprocessing and dataset splitting
- training a custom CNN model
- fine-tuning a pretrained ResNet18 model
- evaluating both models on a held-out test set
- comparing performance using multiple classification metrics

## Models Used

### 1. Custom CNN
A baseline convolutional neural network trained from scratch on the plant image dataset.

### 2. ResNet18 with Transfer Learning
A pretrained ResNet18 model fine-tuned for the plant classification task.

## Results

The transfer learning approach significantly outperformed the baseline CNN:

- **Custom CNN test accuracy:** 74.5%
- **ResNet18 test accuracy:** 98.2%

The models were also evaluated using:
- precision
- recall
- F1-score

## How to Run

1. Clone the repository
2. Install the required libraries
3. Open the notebook
4. Run the cells in order
