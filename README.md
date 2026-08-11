# 🐶🐱 Dog vs Cat Image Classification

A Deep Learning image classification project that identifies whether an input image
contains a **Dog or Cat** using **Transfer Learning with MobileNetV2**.

## 🚀 Project Overview

This project uses a pretrained MobileNetV2 model to extract visual features
from images and a custom classification layer to classify images into two classes:

- 🐱 Cat
- 🐶 Dog

Instead of training a CNN from scratch, MobileNetV2 pretrained on ImageNet
is used as the feature extractor.

## 🧠 Technologies Used

- Python
- TensorFlow
- Keras
- MobileNetV2
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## 🔄 Model Architecture

Input Image  
↓  
MobileNetV2  
↓  
Global Average Pooling  
↓  
Dense Layer  
↓  
Softmax  
↓  
Cat / Dog

## 📊 Model Performance

- Training Accuracy: **99.66%**
- Test Accuracy: **97.50%**
- Training Loss: **0.0179**
- Test Loss: **0.0603**

## 📁 Dataset Structure

```text
image_resized/
├── Cat/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
└── Dog/
    ├── image1.jpg
    ├── image2.jpg
    └── ...

```

## 📓 Project Notebook

The complete implementation of this project is available in the Jupyter Notebook included in this repository.

## 🔮 Future Improvements

- Fine-tune MobileNetV2
- Add data augmentation
- Deploy the model using Streamlit
- Create a FastAPI API
- Deploy the application online

## 📫 Contact

**Fahad Qureshi**

- 🔗 GitHub: [Fahadqureshi0](https://github.com/Fahadqureshi0)
- 💼 LinkedIn: [https://www.linkedin.com/in/fahad-qureshi-aa8a8727b/](YOUR_LINKEDIN_URL)
- 📧 Email: [fahadqureshi.dev@gmail.com](mailto:YOUR_EMAIL)

