Mohamed Gamal El-Saied
ID: 2023037239

🧠 Neural Networks Project
MNIST Handwritten Digit Recognition
📌 Project Overview

This project implements a Multilayer Perceptron (MLP) neural network to classify handwritten digits (0–9) using the MNIST dataset.

The main objective is to build a simple deep learning model, evaluate its performance, and compare different activation functions.

📊 Dataset

The project uses the famous MNIST dataset, which contains handwritten digit images.

Dataset Details:
60,000 training images
10,000 testing images
Image size: 28 × 28 grayscale
Labels: digits from 0 to 9

The dataset is loaded directly using TensorFlow/Keras.

⚙️ Preprocessing Steps

The following preprocessing techniques were applied:

Normalization of pixel values (0–255 → 0–1)
One-hot encoding of labels
Splitting the dataset into training and testing sets
🧠 Model Architecture (MLP)

The neural network is built using a Multilayer Perceptron (MLP) architecture:

Input Layer
Flatten layer converts image size from 28 × 28 → 784
Hidden Layer
Dense layer with 128 neurons
Dropout Layer
Dropout rate: 0.2
Used to reduce overfitting
Output Layer
10 neurons
Softmax activation for classification
🚀 Training Details
Optimizer: Adam
Loss Function: Categorical Crossentropy
Epochs: 10
Validation Split: 20%
🧪 Experiments
Experiment 1
Activation Function: ReLU
Accuracy: ~97.7%
Loss: ~0.080
Experiment 2
Activation Function: Tanh
Accuracy: ~97.1%
Loss: ~0.090
📈 Results Comparison
Model	Activation Function	Accuracy	Loss
Model 1	ReLU	97.7%	0.080
Model 2	Tanh	97.1%	0.090
📊 Visualizations Included
Training vs Validation Loss Curve
Training vs Validation Accuracy Curve
Confusion Matrix
Sample Predictions Visualization
🧾 Evaluation Metrics

The following evaluation metrics were used:

Accuracy (Classification Performance)
Loss Value
Confusion Matrix Analysis
📌 Conclusion

The ReLU activation function achieved better performance than Tanh in terms of both accuracy and loss.

This indicates that ReLU is more suitable for handwritten digit classification using the MNIST dataset and MLP neural networks.
