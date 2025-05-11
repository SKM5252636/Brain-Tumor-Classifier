# 🧠 Brain Tumor Classifier using CNN and Gradio

This project is a deep learning application that uses a Convolutional Neural Network (CNN) to classify brain tumor images into four categories:

- **Glioma**
- **Meningioma**
- **No Tumor**
- **Pituitary**

The system is wrapped in a user-friendly **Gradio interface** for image upload and classification.

---

## 📁 Project Directory Structure

brain_tumor_classifier/
│
├── brain_tumor_classifier.py # Main script containing training and Gradio app
├── README.md # Project documentation
└── Training/ # Dataset folder with categorized images
      ├── glioma/
      ├── meningioma/
      ├── notumor/
      └── pituitary/


---

## 🧠 Model Overview

The model is a custom CNN built using TensorFlow/Keras with the following architecture:

- Convolutional Layers: 3 layers with ReLU activation and Batch Normalization
- Max Pooling Layers
- Global Average Pooling
- Dense Layer with Dropout
- Final Output Layer using Softmax for classification

---

## 🧰 Requirements

Install the necessary libraries before running the project:

```bash
pip install numpy opencv-python tensorflow scikit-learn gradio
```
