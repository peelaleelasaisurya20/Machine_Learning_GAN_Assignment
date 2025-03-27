Generative Adversarial Network (GAN) using CIFAR-10

Introduction:
This repository contains an implementation of a Deep Convolutional Generative Adversarial Network (DCGAN) using TensorFlow and Keras. The model is trained on the CIFAR-10 dataset to generate synthetic images resembling real-world objects.

Project Overview:
GANs consist of two competing neural networks:
Generator: Creates fake images from random noise.
Discriminator: Determines whether an image is real or generated.
These networks are trained in an adversarial manner, improving their performance over time.

Features:
Use CIFAR-10 dataset 
Implements DCGAN architecture with convolutional layers.
Fast training with fewer epochs for quick results.
Generates and saves output images at each epoch.

Workflow:
Load CIFAR-10 dataset and normalize the pixel values to [-1,1].
Define the Generator: Transforms random noise into 32x32x3 images using transposed convolutional layers.
Define the Discriminator: Uses convolutional layers to classify images as real or fake.
Train the GAN: The generator tries to create realistic images, while the discriminator tries to classify them correctly.
Both networks are updated using Binary Crossentropy Loss and Adam Optimizer.
Generate and save images after every epoch.

Installation & Setup:-
To run the project, follow these steps:
Prerequisites:
Ensure you have Python 3 and the required libraries installed.
pip install tensorflow, matplotlib, numpy, keras
Run the Training Script

Output:
The script will generate and save images during training.
