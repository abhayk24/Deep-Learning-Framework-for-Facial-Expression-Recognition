# EmotionVision
### Comparative Analysis of CNN, ResNet50 and Vision Transformer for Facial Expression Recognition

<p align="center">
<img src="https://img.shields.io/badge/Python-3.10+-blue.svg">
<img src="https://img.shields.io/badge/TensorFlow-2.x-orange.svg">
<img src="https://img.shields.io/badge/PyTorch-2.x-red.svg">
<img src="https://img.shields.io/badge/OpenCV-ComputerVision-green.svg">
<img src="https://img.shields.io/badge/License-MIT-lightgrey.svg">
</p>

---

## Project Overview

EmotionVision is a deep learning project that compares three different neural network architectures for Facial Expression Recognition (FER):

- Custom Convolutional Neural Network (CNN)
- Transfer Learning using ResNet50
- Vision Transformer (ViT)

The objective is to analyze how traditional convolutional models compare with modern transformer-based architectures on the FER2013 dataset.

---

## Dataset

**Dataset:** FER2013

- 28,709 Training Images
- 7,178 Test Images
- 7 Emotion Classes
- Image Size: 48 × 48 pixels (resized during training)

### Emotion Classes

- Angry
- Disgust
- Fear
- Happy
- Neutral
- Sad
- Surprise

---

## Models Implemented

### 1. Custom CNN

- Convolution Layers
- Batch Normalization
- Max Pooling
- Dropout
- Fully Connected Layers

---

### 2. ResNet50 (Transfer Learning)

- ImageNet Pretrained Weights
- Feature Extraction
- Fine-tuning
- Global Average Pooling
- Dense Classification Layer

---

### 3. Vision Transformer (ViT)

- Pretrained ViT Backbone
- Transfer Learning
- Self-Attention Mechanism
- Transformer Encoder Blocks
- Classification Head

---

## Performance Comparison

| Model | Accuracy | Precision | Recall | F1 Score |
|--------|----------|-----------|--------|----------|
| CNN | **53.61%** | **54.59%** | **53.61%** | **53.91%** |
| ResNet50 | **61.99%** | **61.39%** | **61.99%** | **61.33%** |
| Vision Transformer | **61.99%** | **61.23%** | **61.99%** | **61.17%** |

---

## Repository Structure

```
EmotionVision/
│
├── notebooks/
│   ├── 01_CNN_Baseline.ipynb
│   ├── 02_ResNet50_TransferLearning.ipynb
│   ├── 03_VisionTransformer.ipynb
│   └── 04_Model_Comparison.ipynb
│
├── README.md
```

---

## Technologies Used

- Python
- TensorFlow / Keras
- PyTorch
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- timm

---

## Author

**Abhay Kesarwani**

Third Year Undergraduate  
Indian Institute of Technology Kanpur

---

## License

This project is intended for educational and research purposes.
