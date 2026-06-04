# TensorFlow MNIST Classification
This project demonstrates a simple neural network built with TensorFlow and Keras to classify handwritten digits from the MNIST dataset.

# Overview
Loads and normalizes the MNIST dataset

Builds a sequential model with:

Flatten layer (28×28 input)

Dense layer (128 neurons, ReLU activation)

Dropout layer (0.2)

Output layer (10 neurons for digit classes)

Trains the model using the Adam optimizer and SparseCategoricalCrossentropy loss

Evaluates performance on test data

# Results
Training accuracy: ~97.6%

Test accuracy: ~97.3%

Loss: ~0.08

 # How to Run
Open the notebook in Google Colab and run all cells sequentially:
tensorflow.ipynb


tensorflow.ipynb
