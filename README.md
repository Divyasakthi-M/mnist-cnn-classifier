#  MNIST Digit Classification using CNN

This project builds a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset. The model achieves over **98% accuracy** on validation and test data using a simple and effective architecture.

---

## Dataset

- MNIST: 70,000 grayscale images (28x28 pixels)
- 60,000 for training, 10,000 for testing
- Built-in from TensorFlow datasets

---

## Model Architecture

- Conv2D(32, 3x3) → ReLU → MaxPooling
- Conv2D(64, 3x3) → ReLU → MaxPooling → Dropout(0.5)
- Flatten → Dense(500) → Dense(10) with softmax

