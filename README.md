# Flower Classification README

This README provides an overview of the Flower Classification project, including objectives, data, model building, evaluation, and reporting instructions.

## 1. Objectives
The objectives of this project are as follows:
1. Become familiar with CNN (Convolutional Neural Networks) models and transfer learning.
2. Apply fine-tuning and analyze the performance of different classifiers on a large image dataset for flower classification.

## 2. Problem Statement
The project involves classifying 104 types of flowers based on their images, which are drawn from five different public datasets. Some classes contain only a specific sub-type of flower, while others contain multiple sub-types.

## 3. Data
### 3.1 Download the Dataset and Understand the Format
(a) Download the dataset from the class's Microsoft Teams or the specified source.

(b) Implement a function to load an image and visualize images from different classes for better understanding.

(c) Display the number of samples in each class to understand the dataset's distribution.

### 3.2 Split Data
(a) Split the training data into two parts: 90% for training and the remaining 10% for validation.

(b) Utilize the validation data during model training as a validation set.

(c) Reserve the test data solely for model evaluation, ensuring it is not introduced during any training steps.

### 3.3 Data Preprocessing
Before feeding images into deep learning models, ensure proper preprocessing:

- Scale the pixel values in images to a suitable range for input to the neural network.

## 4. Build CNN Models
In this section, you will build various CNN models to classify flowers.

### 4.1 Simple Model
(a) Build a simple CNN model from scratch using 2D convolutions, pooling layers, etc.

### 4.2 Famous CNN Architectures
(b) Implement the following famous CNN architectures:
- (a) VGG
- (b) ResNet
- (c) GoogLeNet

### 4.3 Transfer Learning
(c) Utilize pretrained weights for the architecture of choice, instead of training the network from scratch. The ImageNet dataset is commonly used for pretraining CNN architectures.

### 4.4 Ensemble
(d) Explore the ensemble method by integrating multiple models. Ensembling can potentially enhance classification performance.

## 5. Big Picture
Compare the performance of the different models by conducting evaluations on the testing data.

- Compute accuracy and Macro F-Score for each model.
- Generate confusion matrices to identify the most confusing classes.
