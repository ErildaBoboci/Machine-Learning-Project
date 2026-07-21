# Heart Disease Prediction

A machine learning project for predicting the presence of heart disease using clinical patient data from the UCI Heart Disease dataset. This project follows a complete machine learning pipeline, including data exploration, preprocessing, model training and evaluation.

---

## Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can assist healthcare professionals in identifying high-risk patients and supporting clinical decision-making.

This project implements a binary classification system that predicts whether a patient has heart disease based on demographic and clinical features.

The workflow includes:

- Exploratory Data Analysis (EDA)
- Data preprocessing
- Feature engineering
- Model training
- Performance evaluation and comparison

---

## Project Structure

```
heart-disease-project/
│
├── data/
│   └── heart_disease_uci.csv        # Dataset
│
├── notebooks/
│   └── heart_disease.ipynb          # Implementation of the pipeline
│
├── ECG meaning.jpg                  # ECG reference image
│
└── README.md
```

---

## Dataset

**Source:** UCI Heart Disease Dataset

The dataset contains patient information collected from multiple hospitals and includes demographic, clinical, and laboratory measurements.

### Target Variable

A new binary target variable was created:

- **0** → No Heart Disease
- **1** → Heart Disease

---

## Features

Some of the most important features include:

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Maximum Heart Rate (thalch)
- Exercise-Induced Angina (exang)
- ST Depression (oldpeak)
- Slope
- Number of Major Vessels (ca)
- Thalassemia (thal)

---

## Exploratory Data Analysis (EDA)

The notebook includes:

- Dataset inspection
- Missing value analysis
- Descriptive statistics
- Histograms
- Box plots
- Distribution analysis
- Correlation heatmap
- Outlier identification
- Class distribution analysis

---

## Data Preprocessing

The preprocessing pipeline includes:

- Handling missing values
- Encoding categorical variables
- Feature scaling
- Creating the binary target variable
- Train-test split

---

## Machine Learning Pipeline

The project follows these steps:

1. Load the dataset
2. Explore the data
3. Clean and preprocess
4. Split into training and testing sets
5. Train machine learning models
6. Evaluate model performance
7. Compare results

---

## Evaluation

Models are evaluated using common classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC (if applicable)

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-learn
- Yellowbrick

---

