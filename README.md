# 🏭 AI-Powered Industrial Casting Defect Detection

An end-to-end **Computer Vision** project for automated industrial quality inspection using **Transfer Learning** and **Explainable AI (XAI)**. The system classifies casting products as **Defective** or **Acceptable** and visualizes the model's decision-making process using **Grad-CAM**.

---

## 📌 Overview

Manual inspection of casting products is time-consuming, expensive, and prone to human error. This project demonstrates how deep learning can automate the inspection process while maintaining high accuracy and transparency.

The model is built using **Xception**, a pre-trained Convolutional Neural Network (CNN), and fine-tuned for binary classification on an industrial casting dataset.

---

## ✨ Features

- ✅ Transfer Learning using Xception
- ✅ Binary Classification (Defective / Acceptable)
- ✅ Image Data Augmentation
- ✅ Early Stopping & Learning Rate Scheduling
- ✅ Class Weight Handling for Balanced Training
- ✅ Explainable AI using Grad-CAM
- ✅ Confusion Matrix & Classification Report
- ✅ Industrial Quality Inspection Pipeline

---

# 🏗️ Project Workflow

```
Casting Product Images
          │
          ▼
Image Preprocessing
          │
          ▼
Data Augmentation
          │
          ▼
Transfer Learning (Xception)
          │
          ▼
Model Training
          │
          ▼
Prediction
          │
          ▼
Grad-CAM Visualization
          │
          ▼
Quality Inspection Report
```

---

# 🧠 Model Architecture

- Base Model: Xception (ImageNet Pre-trained)
- Input Size: 300 × 300 × 3
- Global Average Pooling
- Fully Connected Layer (256 Units)
- Softmax Output Layer (2 Classes)

---

# 📊 Dataset

**Dataset**

Casting Product Image Data for Quality Inspection

Classes:

- Defective
- Acceptable (OK)

The dataset consists of real industrial casting product images captured during manufacturing inspection.

---

# ⚙️ Tech Stack

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

---

# 📈 Model Performance

| Metric | Score |
|---------|-------|
| Accuracy | **99.16%** |
| Precision | 99%+ |
| Recall | 99%+ |
| F1-Score | 99%+ |

---

# 🔍 Explainable AI

To improve model transparency, **Grad-CAM (Gradient-weighted Class Activation Mapping)** is used.

Grad-CAM highlights the image regions responsible for each prediction, allowing engineers to verify that the model focuses on actual defects instead of irrelevant background features.

---

# 📊 Evaluation

The trained model is evaluated using:

- Confusion Matrix
- Classification Report
- Accuracy
- Precision
- Recall
- F1-Score
- Grad-CAM Visualizations

---

# 🚀 Future Improvements

- Real-time industrial camera integration
- PLC & conveyor belt integration
- Edge deployment (Jetson Nano / Raspberry Pi)
- Multi-class defect classification
- YOLO-based real-time inspection
- Vision Transformer (ViT) implementation

---

# 📂 Repository Structure

```
AI-Powered-Industrial-Casting-Defect-Detection/
│
├── AI-Powered-Industrial-Casting-Defect-Detection.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

# 📄 License

This project is released under the MIT License.

---

# 👨‍💻 Author

**Aditya Biranje**

B.Tech – Artificial Intelligence & Data Science

Passionate about Computer Vision, Explainable AI (XAI), Machine Learning, and Intelligent Manufacturing Systems.
