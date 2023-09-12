# Facial Emotion Detection: Machine Learning Insights
This repository contains the code for an Emotion Classification project using Machine Learning. The project aims to classify facial expressions into different emotional categories using Convolutional Neural Networks (CNNs) and compare the performance with Support Vector Machines (SVMs) and Decision Trees.

# Getting Started
# Prerequisites
To run the code, you'll need the following:

Python (>= 3.6)
TensorFlow (>= 2.0)
scikit-learn
matplotlib

# Data
The dataset used for this project should be organized as follows:

data/
    train/
        class1/
            image1.jpg
            image2.jpg
            ...
        class2/
            image1.jpg
            image2.jpg
            ...
        ...
    test/
        class1/
            image1.jpg
            image2.jpg
            ...
        class2/
            image1.jpg
            image2.jpg
            ...
        ...
        
train/ contains subdirectories for each emotion class, each containing the training images.
test/ contains subdirectories for each emotion class, each containing the test images.

# Code Overview
The code is organized as follows:

Data Preprocessing: Loading and augmenting the dataset using ImageDataGenerator.

Model Building: Constructing a CNN model for emotion classification with three convolutional layers and fully connected layers.

Model Training: Training the CNN model on the training dataset, considering class weights to handle class imbalance.

Model Evaluation: Evaluate the model on the test dataset and generate classification reports and confusion matrices.

Comparison to SVM and Decision Trees: Comparing the CNN model's performance with Support Vector Machines (SVMs) and Decision Trees.

# Results
The code provides various evaluation metrics, including accuracy, classification reports, and confusion matrices, to assess the model's performance. It also compares the CNN model with SVM and Decision Trees.

