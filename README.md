# Razorback Logo Classifier – CNN Project

This repository contains a Convolutional Neural Network (CNN) built in PyTorch to classify Etsy images as:

- **1 – Official Razorback logo**
- **0 – Not an official Razorback logo**


The University of Arkansas requested a model to automatically detect unlicensed Razorback logo usage online.
This project:
Builds a 50-image custom dataset (official vs. non-official logos)
Preprocesses images to 500×500 resolution
Constructs a custom 4-block CNN architecture
Trains/validates the model with CrossEntropyLoss + Adam
Tracks overfitting and applies mitigation techniques
Saves the final model as:
Group_16_CNN_FullModel.ph


This script:

1. Loads images from a folder using `torchvision.datasets.ImageFolder`
2. Applies preprocessing and data augmentation
3. Defines a custom CNN architecture `RazorbackCNN`
4. Trains and validates the model
5. Saves the best-performing model as `Group_16_CNN_FullModel.ph`

