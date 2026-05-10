# 🏥 Healthcare ML Analysis

A machine learning project focused on exploring healthcare data, preprocessing features, and comparing classification models to predict patient test results.

## 📌 Project Overview

This project performs:

* Exploratory Data Analysis (EDA)
* Data preprocessing and feature engineering
* Data encoding and normalization
* Machine learning model training
* Model evaluation and comparison
* Feature importance analysis

The main objective was to practice and demonstrate a complete data science workflow rather than maximize prediction accuracy.

## 📂 Dataset

Dataset used:
[Healthcare Dataset on Kaggle](https://www.kaggle.com/datasets/prasad22/healthcare-dataset?utm_source=chatgpt.com)

The dataset contains healthcare-related patient information including:

* Age
* Gender
* Blood Type
* Medical Condition
* Insurance Provider
* Billing Amount
* Admission Type
* Medication
* Test Results
* and more

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## ⚙️ Project Workflow

### 1. Data Exploration

* Checked dataset structure and data types
* Identified duplicate records
* Explored feature distributions
* Visualized trends using charts and plots

### 2. Data Preprocessing

* Cleaned inconsistent text formatting
* Converted date columns to datetime format
* Created a new feature: `Length of Stay`
* Removed duplicate rows
* Encoded categorical variables
* Normalized numerical features

### 3. Machine Learning Models

The following models were trained and evaluated:

* Logistic Regression
* Decision Tree Classifier
* K-Nearest Neighbors (KNN)

### 4. Evaluation Metrics

Models were evaluated using:

* Accuracy
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Cross-validation

## 📊 Results

| Model               | Accuracy |
| ------------------- | -------- |
| Decision Tree       | 40.61%   |
| K-Nearest Neighbors | 36.47%   |
| Logistic Regression | 33.31%   |

The Decision Tree model achieved the best overall performance on this dataset.

## 📈 Key Takeaways

* Built a complete end-to-end ML pipeline
* Practiced feature engineering and preprocessing techniques
* Learned how to compare multiple classification models
* Explored feature importance interpretation

## 🚀 Future Improvements

Possible future enhancements:

* Hyperparameter tuning
* Advanced ensemble models
* Better feature selection
* More meaningful feature engineering

## 🤖 Note

Parts of this project were developed with the assistance of AI tools for code generation, debugging, and workflow optimization.

## 👤 Author

Asma Alkarbi
