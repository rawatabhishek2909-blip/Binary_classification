# Binary_classification
# 🐴🦓 Binary Animal Classification — Horse vs Zebra
## Overview
A deep learning project that uses a Convolutional Neural Network (CNN) to classify images of horses and zebras using the Horse2Zebra dataset from TensorFlow Datasets.
## 🧠 Model Architecture

3x Conv2D layers (32 → 64 → 128 filters) with ReLU activation
MaxPooling after each conv layer
Flatten → Dense (256) → Dropout (0.4) → Sigmoid output

## 📦 Dataset

Source: TensorFlow Datasets — cycle_gan/horse2zebra
Labels: 0 = Horse, 1 = Zebra
Split: 80% training / 20% validation

## ⚙️ Features

Image preprocessing (resize to 128×128, normalize to [0,1])
Data augmentation (flip, rotation, zoom, contrast)
Learning rate scheduling with ReduceLROnPlateau
Early stopping with best weight restoration

## 📊 Results

Training Accuracy: ~98%
Validation Accuracy: ~96–98%
No overfitting observed in initial training phase

## 🚀 How to Run
bashpip install tensorflow tensorflow-datasets matplotlib numpy
jupyter notebook Animal_Comparison_CNN_Model.ipynb
## 🛠️ Tech Stack
Python · TensorFlow · Keras · TensorFlow Datasets · Matplotlib · NumPy
## 👤 Author
Abhishek Rawat

