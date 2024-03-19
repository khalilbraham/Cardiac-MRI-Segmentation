# Cardiac MRI Classification Project

This project aims to develop an automatic diagnosis system for cardiac pathologies using cardiac magnetic resonance imaging (MRI) data. The project involves several steps, including data preprocessing, left ventricle segmentation, feature extraction, and classification algorithms.

## Table of Contents

1. Problematic
2. Data
3. Left Ventricle Segmentation
4. Feature Extraction
5. Classification Algorithms
6. Results
7. Conclusion

## Problematic

Cardiac pathologies are leading causes of death worldwide, necessitating early identification for effective patient management. The challenge involves classifying MRI images into five diagnostic classes.

## Data

The dataset includes MRI images of the heart for 150 subjects along with segmentations and metadata. It's divided into a training-validation set and a test set.

## Left Ventricle Segmentation

Segmentation of the left ventricle (LV) cavity is crucial for feature extraction. The dice coefficient is used as a loss function for LV segmentation.

## Feature Extraction

Features are extracted manually and using PyRadiomics. The features include intensity-based, texture-based, and shape-based features.

## Classification Algorithms

Various classification algorithms such as LightGBM, MLP, Random Forest, XGBoost, SVM, and Autoencoder Teacher-Student SVM are evaluated.

## Results

Validation accuracies are compared across different models, with SVM and the self-supervised AE-SVM model showing promising results.

## Conclusion

The project involves implementing cutting-edge segmentation, feature extraction, and classification techniques to develop an automatic diagnosis system for cardiac pathologies.

---

### Note:

This readme provides an overview of the project. For detailed implementation and code, please refer to the project files.
