# Decision Tree Implementation and Comparison

## Assignment Title
Decision Tree (DT) Implementation and Comparison

## Project Overview
This project implements and compares two Decision Tree algorithms: CART using the Gini criterion and ID3 using the Entropy criterion. Both models were trained and tuned using Cross-Validation in a fully automated Google Colab workflow.

## Dataset
The dataset used in this project is the Breast Cancer Wisconsin Diagnostic Dataset. The dataset was uploaded to GitHub as `data.csv`, and the Colab notebook loads it automatically using a raw GitHub link.

## Algorithms Used
1. CART Decision Tree using Gini criterion
2. ID3 Decision Tree using Entropy criterion

## Preprocessing Steps
The dataset was preprocessed before model training. Missing values were handled, unnecessary columns were removed, and the categorical target variable was encoded using LabelEncoder.

## Model Tuning
Both CART and ID3 models were tuned using GridSearchCV with Cross-Validation. The tuned parameters were:

- max_depth
- min_samples_split

## Required Visualizations
The notebook generates the following required outputs:

1. Decision Boundary Plot in 2x1 comparison format
2. Confusion Matrix Heatmap in 2x1 comparison format
3. ROC Curve Plot in 2x1 comparison format
4. Evaluation Metrics Bar Chart comparing Accuracy, Precision, Recall, F1 Score, and AUC
5. Decision Tree Structure Visualization

How to Run

Open the Google Colab notebook and click Run All. The notebook automatically loads the dataset from the raw GitHub link, preprocesses the data, trains both Decision Tree models, tunes them using Cross-Validation, and generates all required visualizations.

Submitted By

Name: Umma Habiba
Student Id: 210117
