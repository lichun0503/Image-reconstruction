# Image Reconstruction using Deep Learning

This repository contains code for image reconstruction using deep learning techniques on MNIST, CIFAR-10, and CelebA datasets. The primary focus is to enhance the quality of images using a combination of denoising convolutional neural networks (DnCNN) and other advanced methods.

## Project Structure

- `DnCNN.py`: Contains the implementation of the Denoising Convolutional Neural Network (DnCNN) model.
- `main_reconstruction.py`: The main script for training and evaluating the reconstruction model.
- `utils.py`: Utility functions for data preprocessing, augmentation, and other helper methods.

## Datasets

- **MNIST**: Handwritten digits dataset.
- **CIFAR-10**: Dataset containing 60,000 32x32 color images in 10 different classes.
- **CelebA**: Large-scale face attributes dataset with more than 200,000 celebrity images.

## Requirements

- Python 3.x
- TensorFlow or PyTorch (specify version based on your code)
- NumPy
- Matplotlib
- Any other libraries mentioned in your code files

Install the required packages using:
```bash
pip install -r requirements.txt
Training the Model python main_reconstruction.py
