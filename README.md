# Task-3---Credit-Card-Fraud-Detection
## Overview
This project aims to detect fraudulent credit card transactions using machine learning techniques. The dataset contains transactions made by credit cards in September 2013 by European cardholders. It is commonly used for fraud detection tasks due to its highly imbalanced nature.

## Files
- **`credit_card_fraud.csv`**: The dataset containing features of credit card transactions and a label indicating whether each transaction is fraudulent (1) or legitimate (0).
- **`task3.ipynb`**: A Jupyter Notebook with the complete workflow, including data loading, preprocessing, model training, and evaluation.

## Requirements
- Python 3.x
- Jupyter Notebook
- Libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

## How to Run
1. Install the required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
2. Open the `task3.ipynb` notebook in Jupyter and run all cells.

## Steps
1. **Data Exploration**: Load and visualize the dataset, checking for class distribution and missing values.
2. **Data Preprocessing**: Split the dataset into features and target variable, scale the features, and create training and testing sets.
3. **Model Building**: Train a Random Forest classifier to predict fraudulent transactions.
4. **Evaluation**: Assess the model's performance using accuracy, confusion matrix, and classification report.

## Conclusion
This project demonstrates the process of detecting credit card fraud using machine learning, highlighting the importance of data preprocessing and model evaluation in achieving reliable predictions.

