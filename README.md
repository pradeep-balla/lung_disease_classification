# Lung Disease Classification System

## Overview
This project focuses on creating a Lung Disease Classification System using chest X-ray images. The goal was to develop an automated solution capable of accurately diagnosing different lung conditions, including COVID-19, lung opacity, normal lungs, and pneumonia, through the application of deep learning techniques.

## Problem Statement
The challenge addressed in this project was the need for a fast and accurate method to classify lung diseases from chest X-rays. Traditional diagnostic methods are time-consuming and can be subject to human error, particularly in high-stress environments like hospitals. With the rise of COVID-19, the demand for an efficient, automated system to assist in the diagnosis of lung conditions became even more critical.

## Approach
1. **Dataset Preparation**:
   - A dataset of chest X-ray images was assembled, with 1300 images for each of the four classes: COVID-19, lung opacity, normal, and pneumonia.
   - The dataset was preprocessed and split into training, validation, and test sets to ensure robust model evaluation.

2. **Model Training**:
   - State-of-the-art deep learning models, including ResNet50, Xception, MobileNetV2, VGG16, VGG19, and InceptionV3, were trained on the dataset.
   - These models were fine-tuned to improve their performance for the specific task of lung disease classification.

3. **Ensemble Model Development**:
   - An ensemble model combining the strengths of ResNet50, Xception, and VGG16 was developed.
   - Various ensemble techniques, such as stacking, boosting, and voting, were explored to determine the most effective approach.

4. **Optimization**:
   - Hyperparameter tuning was performed using Grid Search to optimize the performance of the models.
   - Data augmentation techniques were employed to increase the diversity and robustness of the training data.

## Results
The ensemble model demonstrated superior performance, achieving high accuracy in classifying lung diseases from chest X-rays. The web application provides an efficient and user-friendly platform for real-time diagnostics.


## Screenshots

![image](https://github.com/user-attachments/assets/e0bc38f9-2dd4-4a24-8c22-bfdd57dcf2ce)

![image](https://github.com/user-attachments/assets/09c07c58-e08f-4da4-a265-d28257f79849)


## Future Work
- Integration with hospital management systems for seamless deployment in clinical settings.
- Expansion to classify additional lung conditions and other medical imaging tasks.

