# Brain Tumor Classification using CNN | NNDL Project
This project focuses on classifying brain MRI images into tumor vs. no tumor categories using deep learning. It applies a custom-built CNN model using PyTorch, along with real-time performance tracking and visualizations.

## Project Objective
To automate and enhance the detection of brain tumors in MRI scans using convolutional neural networks and evaluate the model's ability to generalize across unseen test data.

## Model Architecture & Flow
Built a custom CNN with convolutional, ReLU, pooling, and fully connected layers

- Applied transforms.Compose() for resizing, normalization, and tensor conversion

- Used DataLoader to iterate over training and test MRI datasets

- Evaluated performance using:

- Accuracy

- Confusion Matrix

- Classification Report

- Included visualization of predictions and intermediate features

## Tech Stack
Python
PyTorch
Torchvision
Scikit-learn
Matplotlib & Seaborn
Jupyter Notebook

## Results
Model successfully learned tumor vs. no tumor patterns

Achieved high classification accuracy

Demonstrated class-wise performance with detailed reports

