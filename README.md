# 🧠 Brain Tumor Classification using CNN

This project detects and classifies brain tumors into one of four categories — `glioma`, `meningioma`, `pituitary`, or `notumor` — using a Convolutional Neural Network (CNN). It includes a Gradio-based web interface for real-time prediction.

## 🚀 Features

- Trains a CNN on MRI images of brain tumors.
- Supports 4 tumor categories.
- Clean preprocessing pipeline.
- Integrated Gradio UI for easy testing.

## 🛠️ Installation

Install dependencies:

```bash
pip install gradio tensorflow opencv-python scikit-learn
```

## 🧠 Model Architecture

The CNN consists of:
- Convolutional layers with ReLU
- Max Pooling
- Batch Normalization
- Dropout for regularization
- Dense output layer with Softmax

## 📁 Dataset Structure

Organize the dataset as:

```
/Brain Tumor Segmentation/Testing/
    ├── glioma/
    ├── meningioma/
    ├── notumor/
    └── pituitary/
```

## ▶️ How to Run

1. Mount Google Drive in Colab (if using):
```python
from google.colab import drive
drive.mount('/content/drive')
```

2. Train the model and launch the interface:
```python
interface.launch()
```

3. Upload an MRI image and get the prediction!

## 📊 Results

Model is trained for 10 epochs and achieves competitive accuracy depending on dataset quality and size.

## 📌 Dependencies

- TensorFlow
- OpenCV
- NumPy
- Gradio
- scikit-learn

## 📷 Demo

![demo](screenshot.png)

## 🤝 Acknowledgments

This project was created as part of the **Naan Mudhalvan** program.
