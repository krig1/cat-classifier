# Logistic Regression Cat Classifier

A binary image classifier built from scratch in Python using a neural network mindset.
Classifies images as cat or non-cat using logistic regression with gradient descent.

## How it works
- Images are flattened and normalized to feed into the model
- Forward propagation computes the sigmoid activation and cross-entropy cost
- Backward propagation computes gradients
- Gradient descent updates weights and bias iteratively

## Results
- Training accuracy: ~99%
- Test accuracy: ~70%

## Dataset
cat vs non-cat dataset from Andrew Ng's Deep Learning Specialization

## Dependencies
- numpy
- h5py
- matplotlib
