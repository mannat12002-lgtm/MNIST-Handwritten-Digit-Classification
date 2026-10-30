# MNIST Handwritten Digit Classification

## 1. Project Overview
This project uses Deep Learning to recognize handwritten digits from 0 to 9 using the MNIST dataset.

## 2. Project Objectives
- Build a neural network model.
- Classify handwritten digit images.
- Evaluate model performance.
- Predict digits accurately.

## 3. Dataset Description
The MNIST dataset contains:
- 60,000 training images.
- 10,000 testing images.
- Image dimensions: 28 × 28 pixels.
- 10 classes representing digits 0–9.

## 4. Technologies Used
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 5. Data Preprocessing
- Loaded the MNIST dataset.
- Normalized pixel values between 0 and 1.
- Visualized sample handwritten digits.

## 6. Model Architecture
- Flatten Layer
- Dense Layer (128 neurons, ReLU)
- Dense Layer (64 neurons, ReLU)
- Output Layer (10 neurons, Softmax)

## 7. Model Training
The model was trained using:
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 5
- Batch Size: 32

## 8. Model Performance
- Test Accuracy: 95.76%
- Test Loss: 0.1814
- Macro F1-score: 0.96
- Weighted F1-score: 0.96

## 9. Evaluation
The model was evaluated using:
- Accuracy score
- Classification report
- Confusion matrix

## 10. Conclusion
The model successfully identifies handwritten digits with approximately 95.76% test accuracy.

## Project Files
- mnist_handwritten_digit_classification.ipynb
- mnist_digit_model.keras
-
