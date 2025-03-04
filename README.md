# Image Classifier

![image](https://github.com/user-attachments/assets/5f412a99-294b-4df2-889b-dfd6bc52a18e)


## Overview
This project implements and compares the performance of Artificial Neural Networks (ANN) and Convolutional Neural Networks (CNN) for image classification on the CIFAR-10 dataset. The dataset consists of 60,000 32x32 color images categorized into the following 10 classes:
- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The primary objective is to analyze the classification accuracy of ANN and CNN models and determine which performs better on this dataset.

## Dataset
The CIFAR-10 dataset is a widely used benchmark dataset for image classification tasks. It contains:
- 50,000 training images
- 10,000 test images
- 10 classes, with 6,000 images per class

## Model Architectures

1. **Artificial Neural Network (ANN)**
  
   An ANN is a type of neural network that consists of multiple layers of fully connected neurons. Each neuron processes input data through weighted connections and activation functions. ANN is effective for structured data but lacks the ability to capture spatial relationships in images.

2. **Convolutional Neural Network (CNN)**
   
   A CNN is a specialized neural network designed for image processing. It consists of convolutional layers that automatically learn spatial hierarchies of features, making it well-suited for tasks like image classification.
