# Generative Adversarial Network for MNIST dataset

This repository contains an implementation of a Generative Adversarial Network (GAN) that can generate MNIST digits using Keras.

## About GANs
GANs are a class of neural networks that learn to generate new data by training a generator network to produce fake data that is difficult for a discriminator network to distinguish from real data. During training, the generator and discriminator networks play a game where the generator tries to produce more realistic data while the discriminator tries to correctly classify the data as real or fake.

## About this project
This project uses Keras, a popular deep learning library, to implement a GAN that can generate realistic MNIST digits. The generator and discriminator networks are both fully connected neural networks with several layers, and are trained using the Adam optimization algorithm. This particular implementation of a GAN is also referred to as a DCGAN (or Deep Convolutional GAN).
