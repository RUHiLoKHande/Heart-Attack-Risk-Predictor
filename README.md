# Heart Disease Prediction Model

## Overview

This project implements a predictive model for assessing the risk of heart disease using a machine learning approach. The model leverages the Random Forest classifier from the Scikit-learn library to analyze patient data and predict the likelihood of heart disease based on various health metrics. This can aid healthcare professionals in identifying patients at risk and making informed decisions.

## Dataset

The model is built using the Heart Disease dataset, which includes a collection of health-related attributes and a binary target variable indicating the presence of heart disease (1 for presence and 0 for absence).

### Features

The dataset consists of the following features:

- **age**: Age of the patient (in years)
- **sex**: Sex of the patient (0 = female, 1 = male)
- **cp**: Chest pain type (0 to 3)
- **trestbps**: Resting blood pressure (in mm Hg)
- **chol**: Serum cholesterol level (in mg/dl)
- **fbs**: Fasting blood sugar > 120 mg/dl (0 = false, 1 = true)
- **restecg**: Resting electrocardiographic results (0 to 2)
- **thalach**: Maximum heart rate achieved
- **exang**: Exercise induced angina (0 = no, 1 = yes)
- **oldpeak**: ST depression induced by exercise relative to rest
- **slope**: Slope of the peak exercise ST segment (0 to 2)
- **ca**: Number of major vessels (0 to 3) colored by fluoroscopy
- **thal**: Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)
- **target**: Diagnosis of heart disease (1 = presence, 0 = absence)

## Model Training and Evaluation

The model was trained on a subset of the dataset, with an 80-20 split for training and testing data. The Random Forest classifier was selected for its robustness and ability to handle both categorical and continuous data.

### Model Performance

The trained model achieved an accuracy of approximately 80% on the test dataset, making it a reliable tool for preliminary assessment of heart disease risk.

## Installation

To run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/heart-disease-prediction.git
