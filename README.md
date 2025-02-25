CNN_Model


This repository contains a simple implementation of a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images from the Fashion MNIST dataset. The goal of this project is to demonstrate the basic architecture and workflow of CNNs for image classification tasks.

Key Features:
Dataset: The model is trained on the Fashion MNIST dataset, which consists of 60,000 grayscale images of 28x28 pixels for training and 10,000 images for testing. The images represent 10 different types of clothing, including t-shirts, trousers, and shoes.
Preprocessing: The images are normalized (scaled between 0 and 1) for better model performance and reshaped to meet the input requirements for CNNs.
Model Architecture:
A simple CNN model with 3 convolutional layers (Conv2D) followed by max-pooling layers (MaxPooling2D).
Flatten layer to convert the 2D matrix into a 1D vector.
Fully connected (dense) layers for classification.
Activation Functions: ReLU activation function is used for hidden layers, and a linear activation function is used for the output layer to predict the class of each image.
Optimizer and Loss Function: The model is compiled with the Adam optimizer and Sparse Categorical Crossentropy loss, making it suitable for multi-class classification tasks.
