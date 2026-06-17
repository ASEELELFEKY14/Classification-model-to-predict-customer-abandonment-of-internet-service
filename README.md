# Customer Churn Prediction for Internet Service Providers

## Overview

This project develops a machine learning classification model to predict customer abandonment (churn) of internet services. Customer churn prediction helps service providers identify customers at risk of leaving and take proactive measures to improve customer retention.

## Problem Statement

Customer churn is a major challenge for internet service providers. Acquiring new customers is often more expensive than retaining existing ones. The goal of this project is to build a predictive model that can classify whether a customer is likely to churn based on demographic and service-related features.

## Objectives

* Analyze customer data and identify factors affecting churn.
* Preprocess and clean the dataset.
* Train and evaluate machine learning classification models.
* Predict whether a customer will abandon the internet service.

## Dataset

The dataset contains customer information, including:

* Customer demographics
* Account information
* Subscription details
* Internet services used
* Billing information
* Contract type
* Payment method
* Churn status (Target Variable)

## Methodology

### 1. Data Preprocessing

* Handle missing values
* Remove duplicates
* Encode categorical features
* Scale numerical features
* Split data into training and testing sets

### 2. Exploratory Data Analysis (EDA)

* Analyze customer distributions
* Visualize feature relationships
* Study churn patterns

### 3. Model Training

Several classification algorithms can be used, such as:

* Logistic Regression
* Decision Tree
* Random Forest
* XGBoost
* Support Vector Machine (SVM)

### 4. Model Evaluation

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook

## Project Structure

```text
customer-churn-prediction/
│
├── Customer_Churn_Prediction.ipynb
├── dataset.csv
├── README.md
└── requirements.txt
```

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/customer-churn-prediction.git
cd customer-churn-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the Jupyter Notebook:

```bash
jupyter notebook Customer_Churn_Prediction.ipynb
```

Execute all notebook cells to preprocess data, train the model, and evaluate performance.

## Results

The trained classification model can predict whether a customer is likely to churn, enabling internet service providers to implement targeted retention strategies.

## Future Improvements

* Hyperparameter tuning
* Feature engineering
* Model deployment using Flask or Streamlit
* Real-time churn prediction dashboard

## License

This project is intended for educational and research purposes.
