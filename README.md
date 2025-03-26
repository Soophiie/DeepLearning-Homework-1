# NYCU Computer Vision 2025 Homework-1

Student ID : 313554802
Name : Sophie Fu

# Introduction
This repository contains my implementation for Homework 1 of the *Visual Recognition using Deep Learning* course. The task is to build an image classifier capable of predicting 100 categories, using only ResNet-based architectures under 100M parameters.

The final model is based on **ResNet50 + transfer learning**, trained in Google Colab, with:

- Custom data augmentation
- Label smoothing
- Class-weighted loss
- Learning rate scheduler
- Early stopping
- Label mapping correction for valid test predictions

# How to install
Run this notebook in **Google Colab**.  
Before running, mount your Google Drive and ensure your dataset is under:  
`/content/drive/MyDrive/data`

Otherwise you should change the data_dir path

## dependencies :
The following librairies are required : 
- Python 3.9+
- PyTorch
- Torchvision
- Matplotlib
- PIL
- tqdm
- early-stopping-pytorch (to install in colab : !pip install early-stopping-pytorch)

# Notes
Only ResNet50 was used (with pretrained weights).
No external data was used.
Final prediction output is stored in prediction.csv, using corrected class labels.
All code is written and executed inside ipynb file.

# Performance snapshot
<img width="787" alt="image" src="https://github.com/user-attachments/assets/f5df9986-253a-4366-9039-a1111480be1a" />

