# Image Classification with Machine Learning and CNNs

This project compares traditional machine learning and deep learning approaches for multi-class image classification. A Random Forest classifier is used as a baseline and evaluated against several Convolutional Neural Network (CNN) architectures with different regularization and optimization strategies.

## Features

* Random Forest baseline
* CNN-based image classification
* Data augmentation
* Class imbalance handling using class weights
* Batch normalization and dropout
* L2 regularization
* 5-fold cross-validation

## Tech Stack

* Python
* TensorFlow/Keras
* Scikit-learn
* NumPy
* Pandas
* Matplotlib

## Files

```text
ml-synbio-final.ipynb    # Complete analysis and model training pipeline
```

## Models Evaluated

* Random Forest
* Baseline CNN
* CNN + Data Augmentation
* CNN + Class Weights
* Stabilized CNN
* Stabilized CNN + L2 Regularization

## Results

CNN-based models significantly outperformed the Random Forest baseline, with the stabilized architectures providing the most consistent performance across validation and cross-validation experiments.

## Author

Deepta Susan Beji
