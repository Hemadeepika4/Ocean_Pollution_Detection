# Ocean Pollution Detection Using Deep Learning

An advanced Deep Learning project for detecting underwater ocean pollution using Convolutional Neural Networks (CNNs), Variational Autoencoders (VAEs), Denoising Autoencoders, and underwater image enhancement techniques.

## Project Overview

Ocean pollution is one of the biggest environmental challenges affecting marine ecosystems and biodiversity. Traditional monitoring systems are expensive, time-consuming, and require significant human effort.

This project proposes an AI-powered solution that:

* Detects underwater pollution
* Classifies polluted and non-polluted underwater images
* Enhances underwater image quality
* Uses Deep Learning for automated marine monitoring

The system combines:

* CNN-based Classification
* Variational Autoencoder (VAE)
* Denoising Autoencoder
* Underwater Image Enhancement
* YOLO-compatible Annotation Visualization

---

# Features

* Underwater Image Preprocessing
* Pollution Classification using CNN
* Variational Autoencoder (VAE) Implementation
* Denoising Autoencoder Implementation
* YOLO Annotation Visualization
* Data Augmentation Pipeline
* Histogram Equalization and CLAHE
* ROC Curve and Confusion Matrix Evaluation
* Real-Time Prediction Pipeline
* Training vs. Validation Performance Visualization

---

# Technologies Used

## Programming Language

* Python

## Deep Learning Frameworks

* TensorFlow
* Keras

## Computer Vision Libraries

* OpenCV
* Pillow (PIL)

## Data Science Libraries

* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

## Development Environment

* Google Colab
* Jupyter Notebook
* GitHub

---

# Dataset Used

The dataset consists of underwater images categorized into:

* Polluted
* Non-Polluted

### Pollutants Included

* Plastic bottles
* Plastic bags
* Wrappers
* Marine debris

### Dataset Link

https://www.kaggle.com/datasets/hemadeepika25/ocean-pollution-dataset

---

# Implemented Modules

## Dataset Loading

* Google Drive Integration
* Dataset Path Management
* Image and Label Loading
* File Handling

## Dataset Visualization

* Random Sample Visualization
* Image Plotting
* Bounding Box Visualization

## Image Preprocessing

* Image Resizing (416 × 416)
* RGB Conversion
* Image Normalization
* Contrast Enhancement

## Underwater Image Enhancement

* Histogram Equalization
* Contrast Limited Adaptive Histogram Equalization (CLAHE)
* Image Denoising

## Data Augmentation

* Image Rotation
* Rescaling
* Dataset Expansion

---

# CNN Model

The custom CNN architecture includes:

* Convolutional Layers
* Max Pooling Layers
* Dense Layers
* Dropout Regularization

---

# Variational Autoencoder (VAE)

The VAE implementation includes:

* Encoder
* Decoder
* Latent Space Sampling

---

# Denoising Autoencoder

The Denoising Autoencoder is used for:

* Noise Reduction
* Underwater Image Reconstruction

---

# Evaluation Metrics

The project evaluates model performance using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC Curve
* AUC Score
* Confusion Matrix
* Classification Report

---

# Model Performance Visualization

The project includes the following visualizations:

* Training vs. Validation Accuracy
* Training vs. Validation Loss
* Confusion Matrix Heatmap
* ROC Curve
* Confusion Matrix Visualization
