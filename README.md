# GAN-based Data Augmentation for Pneumonia Detection

This project explores the use of **GANs (DCGAN and cGAN)** for generating synthetic chest X-ray images in order to improve classification performance.  
We evaluate two deep learning models, **ResNet50** and **Vision Transformer (ViT)**, under different scenarios:
- Training without fine-tuning
- Training with fine-tuning
- Training with GAN-based data augmentation (DCGAN and cGAN)

## Contents
- **DCGAN Training**: Generate synthetic chest X-ray images.
- **cGAN Training**: Conditional image generation (Normal vs Pneumonia).
- **ResNet50 & ViT Evaluation**: With and without fine-tuning.
- **Data Augmentation Integration**: Using GAN-generated images to enrich training.

## Requirements
- Python 3.9+
- PyTorch
- Torchvision
- Matplotlib
- Numpy

Install dependencies:
```bash
pip install -r requirements.txt
