# Deep-Learning-Image-Classifier-with-CNN-and-PyTorch
A PyTorch implementation of a Convolutional Neural Network (CNN) for multi-class image classification on the CIFAR-10 dataset, achieving accurate image recognition across 10 object categories.

Project Overview

This project implements a Convolutional Neural Network (CNN) using PyTorch to perform image classification on the CIFAR-10 dataset. The model is trained to recognize and classify images into 10 different categories, including airplanes, automobiles, birds, cats, deer, dogs, frogs, horses, ships, and trucks.

The CNN architecture consists of multiple convolutional layers, ReLU activation functions, max-pooling operations, and fully connected layers for feature extraction and classification.

Features:
Built using PyTorch
CNN architecture with 3 convolutional blocks
CIFAR-10 dataset support
Data normalization and preprocessing
Adam optimizer for training
CrossEntropyLoss for classification
Model evaluation and accuracy measurement
Easy to modify and extend

Dataset:
The project uses the CIFAR-10 dataset provided by torchvision.

60,000 color images
32 × 32 image resolution
10 classes
50,000 training images
10,000 testing images
