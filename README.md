# Overview :

This project implements a binary image classifier designed to distinguish between images of cats and dogs. Leveraging Convolutional Neural Networks (CNNs) and TensorFlow/Keras, the model is trained on a dataset of labeled images of cats and dogs and aims to predict whether a given input image contains a cat or a dog.

## Features :

1. Data Augmentation : Random transformations are applied to the training images (such as rotations, flips, zooms) to improve model generalization.
2. Model Architecture : A CNN model consisting of multiple convolutional, pooling, and dense layers is used to learn spatial hierarchies of features.
3. Training & Validation : The dataset is split into training and validation sets, with real-time data augmentation applied to the training data for improved robustness.
4. Binary Classification : The model outputs a probability indicating whether the image is a cat (0) or a dog (1), with the decision threshold set at 0.5.
