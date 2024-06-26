# Faster RNN training
Wheat Detection using Faster R-CNN
### Introduction
This repository contains a Jupyter notebook for training a Faster R-CNN (Region-based Convolutional Neural Network) model using PyTorch and torchvision. The model is designed to perform object detection specifically for wheat detection, enabling precise identification and localization of wheat heads in images.

### Model Overview
Faster R-CNN is a two-stage object detection framework. The first stage is a Region Proposal Network (RPN) that proposes candidate object bounding boxes. The second stage extracts features using a CNN and performs classification and bounding box regression on these proposals. This architecture allows for accurate and efficient object detection.

### Model Architecture
Image of the Faster R-CNN Model Architecture
![image](https://github.com/barbarazoani/Faster-RNN-simple-training/assets/96505852/3fa8715f-3a00-4c2a-a14e-83b95297f5a7)

### Training Process
The training process involves several key steps:

1.  Data Preparation: The dataset, containing images and bounding box annotations for wheat heads, is loaded and preprocessed.
2.  Model Initialization: The Faster R-CNN model is initialized with a pre-trained ResNet-50 backbone, and the final layers are adjusted for wheat detection.
3.  Training Loop: The model is trained using Stochastic Gradient Descent (SGD) with momentum, over multiple epochs, to minimize the loss function and improve detection accuracy.
4.  Validation: The model's performance is evaluated on a separate validation set to ensure it generalizes well to new images.


### Example output
![image](https://github.com/barbarazoani/Faster-RNN-simple-training/assets/96505852/c93a3b8e-c146-451c-bfc7-0626da9af07c)
