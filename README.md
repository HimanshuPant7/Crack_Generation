# Crack_Generation
This repository contains code for training a Generative Adversarial Network (GAN) to generate synthetic images of cracks in concrete structures.

## Description

The objective of this project is to generate realistic synthetic images of cracks using a GAN architecture. The GAN consists of a generator and a discriminator. The generator generates fake crack images, while the discriminator tries to distinguish between real and fake crack images.

The code provided here includes the implementation of the WGAN architecture using PyTorch. It also includes a custom dataset class for loading crack images and data loaders for training the GAN model.


## Dataset
The dataset used for training the GAN should be stored in the Google Drive folder "/content/drive/MyDrive/LiuLabels".

## Results
The trained GAN model will generate synthetic crack images during the training process. The generated images will be saved as "generated_images_{epoch}.png". You can visualize these images to evaluate the progress of the GAN model.
