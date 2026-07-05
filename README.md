# Gene Expression Classification Using Machine Learning

## Overview
This project applies Machine Learning techniques to classify stomach cancer samples using gene expression data from the TCGA-STAD dataset. The project includes data preprocessing, exploratory data analysis, model training, and performance evaluation of multiple classification algorithms.

## Objectives
- Analyze gene expression data.
- Preprocess and prepare the dataset for machine learning.
- Train and compare different classification models.
- Evaluate model performance and identify the best-performing model.

## Dataset
The project uses two files:

- `G13-TCGA-STAD_EX.csv` : Gene expression matrix containing gene expression values.
- `G13-TCGA-STAD_Label.csv` : Class labels for each sample (Tumor or Normal).

## Project Workflow
1. Import libraries and load the dataset.
2. Exploratory Data Analysis (EDA).
3. Data preprocessing and feature preparation.
4. Train machine learning models.
5. Evaluate and compare model performance.
6. Present the final results and conclusions.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models
- Logistic Regression
- Decision Tree
- Random Forest
- Multi-Layer Perceptron (MLP)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Repository Structure
```text
Gene-Expression-Classification-ML/
│── Gene_Expression_Classification.ipynb
│── G13-TCGA-STAD_EX.csv
│── G13-TCGA-STAD_Label.csv
│── README.md
│── requirements.txt
```
