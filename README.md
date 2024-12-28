# Image Classification with CIFAR-10 using Convolutional Neural Network (CNN)

Welcome to the **Image Classification using CIFAR-10** project! This project utilizes **Convolutional Neural Networks (CNN)** to classify images from the CIFAR-10 dataset, achieving high performance in automatically identifying objects in 10 different categories.

## 📚 Project Overview

The **CIFAR-10 dataset** consists of 60,000 32x32 color images across 10 classes, with each class having 6,000 images. These classes include:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The goal of this project is to build a robust CNN model to automatically classify these images without manual preprocessing, leveraging the power of deep learning to extract meaningful features directly from the data.

## 🧠 Convolutional Neural Network (CNN)

CNNs are a class of deep learning models specifically designed for processing image data. They are highly effective for tasks such as:

- Image Classification
- Object Detection
- Face Recognition
- Video Processing

With CNNs, the model automatically learns to identify hierarchical features from the raw pixel values, making it particularly effective for image-related tasks.

### Key Features of the CNN Model:
- **Multiple Convolutional Layers** to automatically extract features.
- **Max-Pooling Layers** for downsampling and reducing dimensionality.
- **Fully Connected Layers** for classification.
- **ReLU Activation** for nonlinear feature mapping.

## ⚙️ How It Works

1. **Preprocessing**: The CIFAR-10 dataset is loaded and split into training and testing sets.
2. **Model Architecture**: A CNN model is designed with convolutional, max-pooling, and fully connected layers.
3. **Training**: The model is trained using the training dataset, adjusting weights using backpropagation.
4. **Testing & Evaluation**: The model's performance is tested using the test dataset, and accuracy is reported.
