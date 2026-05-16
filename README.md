Mohamed Gamal El_Saied 
2023037239


🧠 Neural Networks Project — MNIST Handwritten Digit Recognition
📌 Project Overview

This project implements a Multilayer Perceptron (MLP) neural network to classify handwritten digits (0–9) using the MNIST dataset.
The goal is to build a simple deep learning model, evaluate its performance, and compare different activation functions.

📊 Dataset

We use the famous MNIST dataset.

60,000 training images
10,000 testing images
Image size: 28×28 grayscale
Labels: digits from 0 to 9

The dataset is directly loaded using TensorFlow/Keras.

⚙️ Preprocessing Steps
Normalization of pixel values (0–255 → 0–1)
One-hot encoding of labels
Splitting into training and testing sets
🧠 Model Architecture (MLP)

The model is built using a Multilayer Perceptron:

Input Layer (Flatten 28×28 → 784)
Hidden Layer (Dense, 128 neurons)
Dropout Layer (0.2) to reduce overfitting
Output Layer (10 neurons, Softmax activation)
🚀 Training Details
Optimizer: Adam
Loss Function: Categorical Crossentropy
Epochs: 10
Validation Split: 20%
🧪 Experiments

Two experiments were conducted:

Experiment 1
Activation Function: ReLU
Result:
Accuracy: ~97.7%
Loss: ~0.080
Experiment 2
Activation Function: Tanh
Result:
Accuracy: ~97.1%
Loss: ~0.090
📈 Results Comparison
Model	Activation	Accuracy	Loss
Model 1	ReLU	97.7%	0.080
Model 2	Tanh	97.1%	0.090
📊 Visualizations Included
Training vs Validation Loss Curve
Training vs Validation Accuracy Curve
Confusion Matrix
Sample Predictions Visualization
🧾 Evaluation Metrics
Accuracy (Classification Performance)
Loss Value
Confusion Matrix Analysis
📌 Conclusion

The ReLU activation function performed better than Tanh in terms of both accuracy and loss.
This shows that ReLU is more suitable for this type of classification problem.
