# Facial Expression Recognition

### This project implements a Convolutional Neural Network (CNN) for facial expression recognition. The model classifies facial expressions into seven categories using grayscale images and applies data augmentation to enhance performance.

## Model Architecture

The model is built using a sequential CNN architecture with multiple convolutional layers, followed by max pooling, dropout for regularization, and dense layers for classification. Key features of the model:

Convolutional Layers: Three Conv2D layers with increasing filters (64, 128, 256).

Batch Normalization: Applied after each Conv2D layer to stabilize learning.

Dropout: Regularization technique to prevent overfitting.

Fully Connected Layers: Two Dense layers, including a final layer with 7 outputs corresponding to the facial expressions.

## Preprocessing and Augmentation
The dataset undergoes several preprocessing steps before being fed to the model:

Rescaling: Pixel values are rescaled to a range of 0-1.
Augmentation: Includes random rotation, zooming, horizontal flips, and shifts to increase training diversity and model generalization.

# Results
After training for several epochs, the model achieves a reasonable accuracy on the test dataset. Here’s a brief summary of the results:

Training Accuracy: 83.03%
Validation Accuracy: 70.68%

These results can be further improved with fine-tuning of the model architecture, hyperparameters, and additional data augmentation techniques.
