# Medical Data Analysis & Classification using Machine-Learning (KNN)

## Overview

This project focuses on analyzing medical patient data, specifically from the MIMIC dataset, and predicting survival rate. The primary tasks include merging datasets, extracting patient age groups, cleaning and handling missing data, and applying machine learning techniques for classification. 

## Dataset

The project utilizes multiple datasets:

- mimic_train.csv: The main training dataset.

- MIMIC_diagnoses.csv: Contains diagnoses information.

- mimic_X_test.csv: The test dataset.

The datasets contain patient details such as Date of Birth (DOB) and Admission Time (ADMITTIME), which are used to derive age-based insights.

## Key Features

Data Preprocessing:

- Merging the primary dataset with diagnosis data.

- Standardizing column names.

- Handling missing values using KNN Imputation and Simple Imputation.

- Extracting the age variable from Date of Birth.

Machine Learning Models:

- Implements K-Nearest Neighbors (KNN) Classifier for classification.

- Uses cross-validation for model evaluation.

- Feature scaling using StandardScaler from Scikit-Learn.

## Libraries Used

The project is implemented in Python using the following libraries:

- pandas for data manipulation

- numpy for numerical operations

- seaborn and matplotlib for data visualization

- scikit-learn for machine learning models and preprocessing
