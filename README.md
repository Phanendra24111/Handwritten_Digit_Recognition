# CodeAlpha_Handwritten_Digit_Recognition
# ✍️ Handwritten Digit Recognition with CNN

## 📌 Objective
This project builds a **Convolutional Neural Network (CNN)** model to recognize handwritten digits (0–9) from grayscale images using the **MNIST dataset**. The model classifies images into one of ten digit classes based on visual patterns.

---

## 📂 Project Overview

- **Model Architecture**:
  - Conv2D layers with ReLU activation
  - MaxPooling for spatial reduction
  - Dense layers for classification

- **Dataset**:
  - **MNIST** (60,000 training + 10,000 testing images)
  - Each image: 28×28 pixels, grayscale

- **Evaluation Metrics**:
  - Accuracy
  - Confusion Matrix

- **Visualizations**:
  - Sample digit preview
  - Predicted result display
  - Confusion matrix heatmap

---

## ⚙️ Tools & Libraries

- Python 3.x
- TensorFlow / Keras
- matplotlib, seaborn
- numpy

---

## 🧪 Results Summary

- **Test Accuracy**: ~98%
- Excellent generalization on unseen handwritten digits
- Confusion matrix reveals model's strengths & weaknesses

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Run all cells in order
3. GPU recommended for faster training (5 epochs)

---

## 📎 File

- `handwritten_digit_recognition.ipynb`: Full code, training output, and sample predictions.

---

## ✅ Status

✅ Successfully implemented using CNN  
✅ Fully functional on Colab with no manual setup  
✅ Included visual and evaluation outputs for reporting
