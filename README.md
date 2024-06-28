
# Monkeypox Classification System

This repository contains the project files for the Monkeypox Classification System developed using deep learning techniques. The objective of this project is to differentiate Monkeypox from other similar dermatological conditions through image data analysis.

## Abstract

The emergence of Monkeypox as a significant health concern necessitates advancements in rapid and accurate diagnostic methods. This study leverages Convolutional Neural Networks (CNNs) to develop an automated classification system that distinguishes Monkeypox from other conditions. Various CNN architectures, including custom models and pre-trained networks such as VGG16, VGG19, and ResNet50, were evaluated. VGG16 achieved the highest accuracy, underscoring the potential of advanced neural networks in improving diagnostic processes.

## Data Description

The dataset consists of images labeled as Monkeypox or Other conditions, collected through web scraping. The data was divided into training, validation, and test sets in a three-fold cross-validation setup to ensure robust model training and validation. Data augmentation techniques were applied to enhance model generalization.

## Methodology

1. **Data Preprocessing:**
   - Image resizing to 224x224 pixels
   - Normalization of pixel values
   - Data augmentation (random rotations, flips, shifts, brightness adjustments, zooming)

2. **Model Implementation:**
   - Custom CNN
   - Pre-trained models: VGG16, VGG19, ResNet50
   - Cross-validation for model training and validation
   - Evaluation metrics: Accuracy, Precision, Recall, F1-score

3. **Model Evaluation:**
   - Custom CNN: Accuracy ~73.3%
   - VGG16: Accuracy ~77.8%
   - VGG19: Accuracy ~64.4%
   - ResNet50: Accuracy ~66.7%

## Results

VGG16 emerged as the most effective model, achieving the highest accuracy among the evaluated models. The study demonstrates that integrating AI-based techniques can significantly enhance the speed and accuracy of Monkeypox diagnosis.

## Future Work

Future research will explore advanced models like EfficientNetB8 and DenseNet121 to address data imbalance and improve generalization capabilities. The goal is to further enhance the predictive accuracy and reliability of the system in clinical settings.
