# Loan-Status-Classifier: Data Analysis, Modeling, and Scalability

## Overview

This project involves the development of a machine learning model to classify loan statuses using data from the Lending Club dataset (2007–2020Q3). The target variable is binary:
- **0**: Fully Paid
- **1**: Charged Off

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, and the implementation of two modeling approaches.

## Features

- **Data Preprocessing**:
  - Cleaning and dropping irrelevant or high-leakage columns.
  - Handling missing values.
  - Encoding categorical variables and scaling numerical features.

- **Exploratory Data Analysis (EDA)**:
  - Visualizations to understand data distributions and relationships.
  - Identification of key features affecting loan status.

- **Modeling Approaches**:
  - Logistic Regression: Simple and interpretable.
  - Random Forest Classifier: Handles non-linear relationships effectively.

- **Model Evaluation**:
  - Metrics used: Confusion Matrix, Classification Report, Accuracy, and ROC Curve.
  - Feature importance analysis for model explainability.

- **Scalability Discussion**:
  - Dataset size and computational considerations for real-world deployments.

## Dataset

- [Lending Club Dataset (2007–2020Q1)](https://www.kaggle.com/datasets/ethon0426/lending-club-20072020q1)
- Preprocessing steps ensure only loans with statuses `Fully Paid` or `Charged Off` are included.

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/username/loan-status-classifier.git
   cd loan-status-classifier
    ```
2. Download and preprocess the dataset:
   - Download the data from Kaggle and rename the `.gzip` file to `.csv`.
   - Place the dataset in the appropriate directory and run the notebook.

3. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Loan-Status-Classifier.ipynb
   ```

## Contributing

Contributions are welcome! Please fork this repository and create a pull request with your proposed changes.

## License

This project is licensed under the [MIT License](LICENSE).

---
**Author**: Luca Sanfilippo  
**Date**: 12/07/2024