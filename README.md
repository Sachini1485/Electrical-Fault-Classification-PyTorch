# Electrical-Fault-Classification-PyTorch
A PyTorch-based machine learning project for detecting and classifying electrical faults in power systems.

## Overview

This deep learning based project is created for classify electrical faults in power systems using PyTorch, analysing currents and voltages and predict the fault by the model.
The objective of this project is to minimize manual analysis and automate fault detection and classifications.

## Dataset

The dataset contains electrical measurements collected under different fault conditions

### Input Features

- Ia – Phase A Current
- Ib – Phase B Current
- Ic – Phase C Current
- Va – Phase A Voltage
- Vb – Phase B Voltage
- Vc – Phase C Voltage

### Output Classes

| Feature | Description |
|----------|-------------|
| Ia | Phase A Current |
| Ib | Phase B Current |
| Ic | Phase C Current |
| Va | Phase A Voltage |
| Vb | Phase B Voltage |
| Vc | Phase C Voltage |

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-Learn
- Matplotlib
- Seaborn
- Google Colab

## Project Workflow

- Load and explore the dataset
- Create fault labels from fault patterns
- Encode categorical labels
- Split data into training and testing sets
- Standardize input features
- Build a PyTorch neural network
- Train the model using mini-batch learning
- Evaluate performance using accuracy, classification report, and confusion matrix
- Demonstrate fault prediction on new input values

## Neural Network Architecture

Input Layer: 6 Features

Hidden Layers:

- 128 Neurons + ReLU
- 64 Neurons + ReLU
- 32 Neurons + ReLU

Output Layer:

- 6 Fault Classes

Regularization:

- Dropout Layer

Optimizer:

- Adam

Loss Function:
  CrossEntropyLoss

## Results

- Test Accuracy: 86%
- Weighted F1-Score: 0.86

## Author

Sachini M Thilakarathna

Electrical and Electronic Engineering Undergraduate



