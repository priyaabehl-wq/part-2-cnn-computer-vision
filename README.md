# Part 2 - CNN Computer Vision Project

## Problem Identification
This dataset represents an image classification problem.

The CNN model classifies manufacturing product images into one of four categories:
- normal
- scratch
- dent
- stain

## Dataset Exploration
- Number of classes: 4
- Total images: 480

### Class Distribution
class
normal     120
scratch    120
dent       120
stain      120

## Image Preprocessing
- Resized images to fixed dimensions
- Normalized pixel values
- Train-test split performed
- Augmentation can be applied using ImageDataGenerator

## CNN Architecture
- Convolution Layers
- ReLU Activation
- MaxPooling Layers
- Flatten Layer
- Dense Layer
- Softmax Output Layer

## CNN Concepts

### What is Convolution?
Convolution extracts important features such as edges and textures from images.

### Why is Pooling Used?
Pooling reduces image dimensions and computation while keeping important features.

### Why is ReLU Commonly Used?
ReLU helps the network learn non-linear patterns efficiently and avoids vanishing gradients.

### Why are CNNs Better for Images?
CNNs automatically learn spatial image features unlike regular neural networks.

## Business Use Case
This solution can be used in manufacturing quality inspection to automatically detect defects in products during production.

## Repository Structure
```
part-2-cnn-computer-vision/
│
├── README.md
├── notebook.ipynb
├── requirements.txt
├── sample_predictions/
│   └── prediction_outputs.png
└── results/
    ├── accuracy_loss_curves.png
    └── confusion_matrix.png
```
