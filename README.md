# Handwritten-Digits-Prediction

📌 Project Overview

The Handwritten Digits Recognition project uses the MNIST dataset to train a Convolutional Neural Network (CNN) for classifying handwritten digits (0–9). The goal is to accurately identify digits from images, making it useful for applications like postal mail sorting, bank cheque processing, and digitizing handwritten documents.

📂 Project Workflow
1. Data Loading & Preprocessing:

Loaded the MNIST dataset from tensorflow.keras.datasets.
Normalized pixel values from 0–255 to 0–1 for faster training.
Reshaped images to match CNN input requirements.

2. Model Building & Training:

Built a CNN using TensorFlow/Keras with convolution, pooling, and dense layers.
Compiled the model with categorical cross-entropy loss and Adam optimizer.
Trained the model on training data with validation split for monitoring.

3. Evaluation & Prediction:

Evaluated model performance on the test set using accuracy score.
Visualized sample predictions with actual vs. predicted labels.
Tested the model on custom handwritten digit images.

🛠 Technologies Used:
Python – Core programming language.
NumPy, Pandas – Data manipulation.
Matplotlib – Visualization of digits and predictions.
TensorFlow/Keras – Deep learning framework for CNN.
