# Home Quote Prediction with PySpark

## Overview
This project explores the application of PySpark-based machine learning models to predict home insurance quote conversions. It leverages distributed computing for scalable training and evaluation of classification models using a large real-world dataset.

## Architecture Diagram
The architecture of the pipeline includes the following stages:
- Data Loading
- Data Understanding & Preprocessing
- Model Training (LR, RF, GBT)
- Model Evaluation (Accuracy, AUC)
- Visualization (Confusion Matrix, AUC Curve, Feature Importance)


## Features
- Preprocessing and cleaning of 290-feature dataset with 200,000 records
- Classification using Logistic Regression, Random Forest, and Gradient Boosted Trees
- Evaluation using Accuracy, AUC, 
- Visual output including AUC curves and feature importance plots
- Executed on distributed Kaggle Notebook with Tesla P100 GPU

## Dataset
- **Samples**: 200,000
- **Features**: 290 (numerical and categorical)
- The dataset includes anonymized features related to user quotes and conversions.
- Source: ##   [Google Drive link](https://drive.google.com/drive/u/0/folders/1ntRZDjHYmaJn6RrwA5yz7itMbOaJhder).


## Methodology
1. **Data Understanding**: Initial analysis to inspect shape, types, and imbalance.
2. **Preprocessing**: Null handling, encoding, and standardization.
3. **Modeling**: Trained three models—Logistic Regression, Random Forest, Gradient Boosted Trees.
4. **Evaluation**: Used metrics like Accuracy, AUC, Confusion Matrix
5. **Visualization**: Plotted confusion matrices, ROC curves, and feature importances.

## Technologies Used
- Apache Spark (PySpark MLlib)
- Python 3.11+
- Pandas & Matplotlib
- Kaggle Notebooks with Tesla P100 GPU
- Jupyter Notebook Interface

## Setup Instructions
1. Clone the repository:
```bash
git clone https://github.com/yourusername/home-quote-prediction.git
```
2. Upload to Kaggle or Spark environment with PySpark setup.
3. Open and run the `main_notebook.ipynb`.

## How to Reproduce
- Ensure Spark is initialized.
- Run preprocessing cells to prepare data.
- Train each model cell-by-cell.
- Evaluate results and generate visualizations.

## Model Performance
| Model              | Accuracy | AUC  |
|-------------------|----------|------|
| Logistic Regression | 0.91     | 0.94 |
| Random Forest       | 0.93     | 0.96 |
| GBT                 | 0.94     | 0.97 |

## Visualizations
- ROC/AUC Curves
- Confusion Matrices



