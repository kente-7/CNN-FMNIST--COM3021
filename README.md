# Neural Network Image Classification with TensorFlow

A supervised machine learning project applying neural networks to a real-world classification problem using TensorFlow and Python.

This project was completed as part of my Computer Science degree at the University of Exeter.
The objective was to design, train, and evaluate a neural network model for image classification on the FMNIST dataset, as well as using two pre-trained models in google cloud, focusing on model architecture, optimisation, and performance evaluation.

## Dataset

- Source: Fashion MNIST dataset (https://www.kaggle.com/datasets/zalando-research/fashionmnist)
- Size: 70,000 samples
- Features: numerical / categorical
- Target variable: Item label

## Methods & Tools

- Python
- TensorFlow / Keras
- NumPy, Pandas
- Data preprocessing & feature scaling
- Train/validation/test split
- Model evaluation (accuracy, loss, confusion matrix)

## Approach

- Built a feedforward neural network
- Hyperparater tuning 
- Used ReLU activation and softmax output
- Optimised using Adam optimiser
- Applied early stopping to prevent overfitting

## Results

- Final test accuracy: 92%
- Observations:
  - Model performance improved with increased hidden units
  - Overfitting observed without regularisation
