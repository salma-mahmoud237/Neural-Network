# Neural-Networks

code link in colab: 

(https://colab.research.google.com/drive/1UIeSterLqfL6B6_VUW9MIw3HJiKh67uD?usp=sharing)

Dataset Link:

https://github.com/zalandoresearch/fashion-mnist but i install it by PyTorch (download=True)

FashionMNIST Classification using MLP Neural Network

This project implements a Multi-Layer Perceptron (MLP) model using PyTorch to classify images from the FashionMNIST 

dataset.

Project Overview

The goal of this project is to build and compare neural network models for image classification using different 

hyperparameters and activation functions.

The project includes:

Data preprocessing

Training and validation

Model evaluation

Accuracy and loss visualization

Early stopping

Performance comparison

Dataset Used:

FashionMNIST

Dataset Description: FashionMNIST is a dataset of grayscale clothing images consisting of 10 classes such as:

T-shirt

Trouser

Pullover

Dress

Coat

Sandal

Shirt

Sneaker

Bag

Ankle boot

Image Size:

28x28 grayscale images

Number of Classes:

10

Technologies Used

Python

PyTorch

Torchvision

NumPy

Matplotlib

Scikit-learn

Data Preprocessing

The following preprocessing steps were applied:

Resize images to 28x28

Convert images to tensors

Normalize pixel values

Split dataset into:

Training set

Validation set

Test set

Data augmentation techniques used:

Random Horizontal Flip

Random Rotation

Model Architecture

Model 1

Activation Function: ReLU

Hidden Layers: 128 neurons

Optimizer: Adam

Learning Rate: 0.001

Model 2

Activation Function: Sigmoid

Hidden Layers: 256 neurons

Batch Normalization

Dropout Regularization

Optimizer: Adam

Learning Rate: 0.0005

Training Features

CrossEntropyLoss

Early Stopping

Validation Monitoring

Accuracy Tracking

Loss Tracking

Results

The models were evaluated using:

Training Accuracy

Model1:

Test Accuracy: 85.58%

Test Loss: 0.4455

Model2:

Test Accuracy: 88.27%

Test Loss: 0.3256

