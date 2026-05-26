# Customer Churn Prediction

This repository contains a machine learning project focused on predicting customer churn in the banking sector using supervised classification models.

The objective of the project is to identify customers likely to leave the bank by analysing demographic, financial and behavioural variables through exploratory data analysis, feature engineering and machine learning techniques.

## Main objectives

- Analyse customer churn patterns in banking data
- Perform exploratory data analysis and visualisation
- Detect class imbalance and outliers
- Preprocess and transform structured data
- Build supervised classification models
- Compare model performance across different algorithms
- Evaluate models using classification metrics
- Interpret model predictions and feature importance

## Dataset

The dataset contains customer-level information including:

- Credit score
- Geography
- Gender
- Age
- Tenure
- Account balance
- Number of products
- Credit card ownership
- Active membership status
- Estimated salary
- Customer churn label (`Exited`)

The notebook automatically downloads the dataset during execution.

## Repository structure

- `Customer_Churn_Detection.ipynb`  
  Main notebook containing the full machine learning workflow.

- `utils.py` *(optional, if present)*  
  Helper functions used for visualisation and model evaluation.

- `requirements.txt`  
  Python dependencies required to run the project.

## Machine learning workflow

The project includes:

### Exploratory Data Analysis (EDA)

- Distribution analysis
- Churn segmentation analysis
- Outlier detection
- Boxplots and violin plots
- Correlation analysis
- Class imbalance inspection

### Data preprocessing

- Missing value handling
- Label encoding
- One-hot encoding
- Feature scaling
- Train-validation-test split

### Classification models

The notebook compares several supervised machine learning algorithms:

- Logistic Regression
- Support Vector Machine (SVM)
- K-Nearest Neighbours (KNN)
- Decision Tree
- Random Forest
- LightGBM

### Model evaluation

Models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- ROC curves
- Confusion matrices
- Feature importance analysis

## Technologies used

- Python
- Pandas
- NumPy
- Scikit-learn
- LightGBM
- Matplotlib
- Seaborn

## How to run the project

Clone the repository and install the required packages:

```bash
pip install -r requirements.txt
