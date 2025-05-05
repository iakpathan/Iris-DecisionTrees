# Iris-DecisionTrees
```
# Iris Dataset Decision Tree Classification

## Overview
This project demonstrates the implementation of **Decision Trees** for classifying flowers in the **Iris dataset**. The dataset contains **150 samples** of iris flowers with four features:
- Sepal length
- Sepal width
- Petal length
- Petal width
```

## Dependencies
To run this project, install the following dependencies:
```bash
import pandas as pd
from sklearn.datasets import load_iris
from sklearn.model_selection import train_test_split
from sklearn.tree import DecisionTreeClassifier
from sklearn.metrics import classification_report
from sklearn.tree import plot_tree
import matplotlib.pyplot as plt


```
###Why Decision Trees
```
The Iris dataset is relatively small, well-structured, and contains clear numerical features. Decision Trees (DT) are a great fit because:
- Interpretability – The model is easy to visualize and understand. You can follow the decision-making process step by step.
- Handles Multi-Class Classification – The Iris dataset has three species (Setosa, Versicolor, Virginica), and DTs handle multi-class problems efficiently.
- Feature Importance – Decision Trees automatically determine which features (sepal length, petal width, etc.) are most relevant for classification.
- Non-Linear Boundaries – Unlike linear models, DTs can capture complex relationships between features.
- No Need for Scaling or Normalization – Decision Trees work well with raw data, without requiring preprocessing like standardization.
- Efficiency with Small Datasets – Since Iris has only 150 samples, Decision Trees train quickly compared to more complex models.
- Resistance to Overfitting with Pruning – Techniques like max depth limitation and pruning help prevent overfitting, improving generalization
```
###Evaluation metrics
```
Each sample is labeled as **Setosa, Versicolor, or Virginica**.
pip install pandas scikit-learn matplotlib seabornThe classification report provides key metrics:
- Precision – Percentage of correctly predicted positive instances.
- Recall – Ability to detect all positive instances.
- F1-score – Balance between precision and recall.
- Support – Number of actual occurrences of each class.
