# Parking Spot Classifier

## Overview

This project focuses on creating a machine learning classifier to determine whether a parking spot is empty or occupied. The classifier is trained on a dataset of images, and a Support Vector Machine (SVM) is utilized for the classification task. The trained model is then saved for future use in parking spot detection applications.

## Features

- **Image Dataset:** The dataset consists of images categorized as "empty" and "not empty" parking spots.
- **Machine Learning Model:** A Support Vector Machine (SVM) is employed for training the classifier.
- **Grid Search:** Model hyperparameters are fine-tuned using Grid Search for optimal performance.
- **Accuracy Evaluation:** The model's accuracy is assessed on a test set to measure its effectiveness in spot classification.
- **Model Persistence:** The trained SVM model is saved using pickle for easy retrieval and integration into other projects.

## Usage

To train the classifier or evaluate its performance:

```bash
python parking_spot_classifier.py

