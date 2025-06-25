# Fashion MNIST Image Classifier

## Overview

This project implements a convolutional neural network (CNN) for image classification on the Fashion MNIST dataset. Built using TensorFlow and Keras, the model learns to categorize grayscale fashion product images into ten classes, providing a clear demonstration of an end-to-end deep learning workflow.

---

## Key Features

* **Automated Data Pipeline**: Downloads and preprocesses the Fashion MNIST dataset—normalizes pixel values and encodes labels.
* **Custom CNN Architecture**: Stacks convolutional, pooling, and fully connected layers with dropout regularization for improved generalization.
* **Configurable Training Pipeline**: Adjustable hyperparameters (epochs, batch size, learning rate) with model checkpointing.
* **Comprehensive Evaluation**: Generates accuracy and loss curves, confusion matrix, and classification report for in-depth analysis.
* **Visualization Dashboard**: Displays sample predictions alongside true labels to facilitate qualitative assessment.

---

## Dataset Details

* **Source:** [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) by Zalando Research.
* **Composition:** 70,000 28×28 grayscale images split into 60,000 training and 10,000 test samples across 10 categories (e.g., T-shirt, Trouser, Pullover).

---

## Technology Stack

* **Language:** Python
* **Frameworks & Libraries:**

  * NumPy & Pandas
  * Matplotlib & Seaborn
  * Scikit-learn
  * Jupyter Notebook

---

## Performance & Results

* **Test Accuracy:** \~90% final accuracy on the held-out test set.
* **Learning Curves:** Demonstrate convergence and minimal overfitting through training and validation metrics.
* **Confusion Matrix & Report:** Highlight precision and recall per class for targeted insights.

--

## Acknowledgments

* Zalando Research for the Fashion MNIST dataset.
* Open-source contributors for libraries and tools used in this project.
