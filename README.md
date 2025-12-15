# CIFAR-10 Image Classification with CNN

## Project Overview
A deep learning project demonstrating the implementation of a Convolutional Neural Network (CNN) to classify images from the CIFAR-10 dataset (vehicles, animals, etc.). The goal was to build an efficient model capable of generalizing well on unseen data.

**Key Results:**
* Achieved **Validation Loss of 0.54**, indicating strong generalization capability.
* Successfully mitigated overfitting through architectural adjustments and data preprocessing.

## Tech Stack
* **Language:** Python
* **Libraries:** TensorFlow/Keras, NumPy, Matplotlib
* **Dataset:** CIFAR-10 (10 classes including airplanes, cars, birds, etc.)

## Architecture & Implementation
The model utilizes a sequence of Convolutional layers followed by Max Pooling and Dropout layers to extract features and reduce spatial dimensions. The final classification is performed by Dense layers.
* **Input:** 32x32 pixel RGB images.
* **Loss Function:** Categorical Crossentropy.
* **Optimizer:** Adam.
