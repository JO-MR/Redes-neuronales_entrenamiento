# 🍷 Wine Quality Prediction Using Neural Networks (TensorFlow & Keras)

This project implements a complete **Deep Learning pipeline** to predict wine quality based on physicochemical attributes.  
It applies neural network modeling techniques using **TensorFlow** and **Keras**, showcasing a clean and professional workflow for structured data prediction tasks.

---

## Project Overview

The goal of this project is to build and evaluate several fully-connected neural network architectures capable of predicting the quality of wine from numerical features such as acidity, sugar content, pH, sulphates, density, and more.

The project demonstrates:

- End-to-end machine learning workflow  
- Neural network training with Keras  
- Data preprocessing and normalization  
- Model experimentation and tuning  
- Evaluation using regression and classification metrics  
- Visual analysis of training performance  

This notebook is fully reproducible and designed as a professional demonstration of deep learning applied to tabular data.

---

## Features

### 🔹 Data Preparation
- Data loading from CSV  
- Feature/label separation  
- Min-Max or Standard Scaling  
- Train/validation/test split  

### 🔹 Model Development
Multiple network architectures evaluated using:

- Dense layers  
- Dropout regularization  
- Activation functions (ReLU, Sigmoid, Softmax)  
- Optimizers such as Adam  
- Loss functions for regression or classification  

### 🔹 Model Evaluation
- Loss curves  
- Accuracy or MAE/MSE depending on the formulation  
- Confusion matrix (if classification)  
- Error distribution plots  
- Comparison across model variants  

## 📂 Project Structure
wine-quality-nn/
│
├── notebooks/
│ └── wine_quality_nn.ipynb # Main notebook (clean & ready)
│
├── data/
│ └── winequality.csv # Dataset (optional)
│
├── README.md
└── requirements.txt


