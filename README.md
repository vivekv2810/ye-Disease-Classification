# Eye Disease Classification Using Deep Learning

## Overview

The Eye Disease Classification project aims to develop a robust model for the automated classification of retinal images into four distinct disease types: Glaucoma, Cataract, Normal, and Diabetic Retinopathy. Leveraging a diverse dataset sourced from reputable repositories, the project employs a Convolutional Neural Network (CNN) architecture, with a focus on utilizing the pre-trained VGG19 model for its image feature extraction capabilities.

## Dataset

The dataset used in this project consists of retinal images carefully curated from Kaggle, ensuring a balanced representation of four disease types.
 
Dataset link: https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification.

## Model Architecture

The chosen model architecture is based on the VGG19 CNN, known for its effectiveness in image classification tasks. Key details about the model's architecture, input size, convolutional layers, pooling, activation functions, and fully connected layers are provided in the Report.

## Data Processing

The dataset undergoes meticulous processing to prepare it for model training. This involves loading images, organizing them into a DataFrame, and creating data generators for training and validation. Data augmentation techniques, such as rotation and zooming, are applied to enhance the model's generalization capabilities.
