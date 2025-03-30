# stroke

# Stroke Prediction Model

A machine learning project that uses an Artificial Neural Network (ANN) to predict stroke risk based on various health indicators.

## Overview

This project implements a deep learning model to predict the likelihood of stroke occurrence using patient health data. The model is built using TensorFlow and achieves robust prediction accuracy through careful feature engineering and model architecture design.

## Features

- Data preprocessing and standardization
- Neural network with dropout layers for regularization
- Performance visualization and metrics
- Binary classification for stroke prediction

## Dataset

The dataset includes the following features:
- Age
- Gender
- Socioeconomic Status (SES)
- Hypertension
- Heart Disease
- BMI (Body Mass Index)
- Average Glucose Level
- Diabetes
- Smoking Status

## Model Architecture

- Input Layer: 9 features
- Hidden Layer 1: 64 neurons with ReLU activation
- Dropout Layer (30%)
- Hidden Layer 2: 32 neurons with ReLU activation
- Dropout Layer (20%)
- Hidden Layer 3: 16 neurons with ReLU activation
- Output Layer: 1 neuron with Sigmoid activation

## Requirements

- Python 3.11+
- TensorFlow
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Usage

1. Clone the repository on Replit
2. Ensure the dataset is in the `attached_assets` folder
3. Run the main script:
   ```bash
   python main.py
   ```

## Output

The model generates:
- Training and validation accuracy metrics
- Classification report
- Visual plots of training history saved as 'training_history.png'

## License
kaggle
This project is open source and available under the MIT License.
