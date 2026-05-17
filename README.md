# 🧠 Neural Networks Project - MNIST Classification

## 👨‍💻 Author

Mohamed Gamal Elsaied

## 📌 Project Description

This project implements a Multilayer Perceptron (MLP) neural network for handwritten digit classification using the MNIST dataset.

The model is trained to recognize handwritten digits from 0 to 9.

---

## 📊 Dataset

Dataset Used: MNIST Dataset

Dataset Link:
https://keras.io/api/datasets/mnist/

The dataset contains:
- 60,000 training images
- 10,000 testing images
- Image size: 28x28 pixels

---

## ⚙️ Data Preprocessing

The following preprocessing steps were applied:

- Normalization of pixel values
- One-Hot Encoding for labels
- Splitting data into training and testing sets

---

## 🧠 Model Architecture

The implemented model is a Multilayer Perceptron (MLP) consisting of:

- Input Layer
- Hidden Layer
- Dropout Layer
- Output Layer

Activation Functions Used:
- ReLU
- Tanh

Loss Function:
- Categorical Crossentropy

Optimizer:
- Adam

---

## 🚀 Training

The model was trained using:
- Epochs = 10
- Validation Split = 20%

Training performance was monitored using:
- Loss
- Accuracy

---

## 🧪 Experiments

Two experiments were performed:

### Experiment 1
Activation Function: ReLU

Results:
- Accuracy: 97.72%
- Loss: 0.0801

---

### Experiment 2
Activation Function: Tanh

Results:
- Accuracy: 97.16%
- Loss: 0.0902

---

## 📈 Visualizations

The project includes:
- Training vs Validation Loss Curves
- Training vs Validation Accuracy Curves

---

## 📋 Results Comparison

| Model | Activation Function | Accuracy | Loss |
|------|--------------------|----------|------|
| Model 1 | ReLU | 97.72% | 0.0801 |
| Model 2 | Tanh | 97.16% | 0.0902 |

---

## ▶️ How to Run

1. Open the notebook in Google Colab
2. Run all cells step by step
3. View training results and graphs

---

## 📁 Project Files

```text
MNIST_MLP_Project.ipynb
README.md
Loss Curve.png
Accuracy Curve.png
