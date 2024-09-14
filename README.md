# CycleGAN Monet Style Transfer

This project implements a CycleGAN to perform style transfer between normal photos and Monet-style paintings. Using TensorFlow, the model is trained to translate images into Monet-style paintings and vice versa. The project also includes functionality to convert a given image into Monet-style using a pre-trained model and display the results.


## Overview

The goal of this project is to apply **CycleGAN** to translate normal photos to Monet-style paintings and vice versa. The two key tasks are:
- Photo to Monet translation.
- Monet to Photo translation.

We trained the model on a dataset of real photos and Monet paintings, leveraging TensorFlow and PyTorch frameworks.

### Key Features
- **CycleGAN Training**: Train CycleGAN models for style transfer between two domains (Photo and Monet).
- **Image-to-Image Translation**: Generate Monet-style images from photos using the pre-trained model.
- **Model Persistence**: Save and load trained models in `.pth` format.
- **Image Display**: Show both the input photo and generated Monet-style image side by side.
