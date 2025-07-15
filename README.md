# 🧠 Brain Tumor Detection using CNN

This project uses Convolutional Neural Networks (CNN) to classify brain MRI scans as either **tumor** or **no tumor**. It's a binary image classification task developed using TensorFlow/Keras, with data augmentation and performance optimization techniques.

---

## 📁 Dataset

The dataset consists of MRI images organized into two folders:

- `yes/` – contains MRI images with brain tumors  
- `no/` – contains MRI images without tumors  

**Source**: Public dataset from [Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection)

---

## 🏗️ Model Architecture

A custom CNN model was built with the following architecture:

- 3× Convolutional layers with ReLU + MaxPooling
- Dropout layers for regularization
- Flatten → Dense layers for binary classification
- Final activation: **Sigmoid**

> Optionally, the model can be enhanced using **Transfer Learning** with architectures like VGG16, MobileNet, or ResNet.

---

## ⚙️ How to Run

1. Upload the dataset (`brain_tumor_dataset.zip`) to your environment  
2. Run the notebook or script step by step  
3. The dataset is split:
   - 70% for training
   - 15% for validation
   - 15% for testing

