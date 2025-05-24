# Multi-Task_Model-with_Keras
A Keras-based multi-task learning model performing simultaneous regression and classification using shared neural network layers.

This project demonstrates how to build and train a **Multi-Task Learning (MTL)** model using **Keras**. The model is capable of solving more than one task simultaneously, making it efficient and powerful for real-world machine learning applications.

## 🚀 Project Overview

Multi-task learning is a type of machine learning where a single model is trained to handle multiple tasks at once. In this project, we create a neural network that performs **both regression and classification** using shared layers. This approach reduces training time and improves performance by leveraging domain-specific information from related tasks.

## 📚 What’s Inside?

- 📦 Keras Functional API implementation
- 🔗 Shared base layers for multi-task architecture
- 🎯 Task-specific output heads
  - **Regression Head:** Predicts a continuous value
  - **Classification Head:** Predicts a categorical label
- 📊 Custom loss weighting and metrics tracking
- 📈 Visualization of loss and accuracy for both tasks

## 🛠️ Technologies Used

- Python 🐍
- TensorFlow / Keras 📦
- NumPy 📊
- Matplotlib 📉

- 📌 Use Cases
Predicting house prices (regression) and region classification

Image captioning with classification and sequence generation

Multimodal data modeling (e.g., text + image)
