# CXR-PFT
This repository contains the implementation of models and methods from the paper "Comparison of Models and Methods: Predicting Pulmonary Function Test Scores from Chest X-Rays". It focuses on predicting pulmonary function test (PFT) scores from chest X-ray images using deep learning techniques.

The code employs a multi-input neural network that integrates image features (DenseNet121) and patient metadata (e.g., age, BMI). It includes robust data preprocessing, a custom weighted loss function, training optimizations (early stopping, learning rate scheduler), and detailed performance evaluation metrics such as MAE, Pearson correlation, and confusion matrices. Visualizations like scatter plots and residuals are provided to aid in analyzing model performance.
