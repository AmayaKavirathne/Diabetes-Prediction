# Diabetes_Prediction_Model

This repository contains a Python script for building a neural network-based model to predict diabetes using the Pima Indian Diabetes dataset. The code utilizes the TensorFlow and scikit-learn libraries for building and evaluating the model. The dataset is preprocessed, oversampled to handle class imbalance, and then fed into a neural network for training and evaluation.

# Requirements
- Python 3.x
- NumPy
- Pandas
- Matplotlib
- scikit-learn
- TensorFlow
- imbalanced-learn (imblearn)

# Dataset
The dataset used for this project is the Pima Indian Diabetes dataset (diabetes.csv). \
It contains the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age\
The target variable is 'Outcome,' indicating the presence (1) or absence (0) of diabetes.

# Results
After training the model, the script displays the accuracy and loss metrics on the training, validation, and test sets.

Feel free to modify the hyperparameters, architecture, or other aspects of the code to experiment with different configurations and improve the model's performance.
