# 🩺 Heart Disease Prediction using Decision Tree

## 📌 Overview

This project applies a **Decision Tree Classifier** to predict the presence of heart disease based on patient health data. It includes **data exploration, preprocessing, visualization, model training, and evaluation**. The goal is to demonstrate the interpretability and predictive power of decision trees in healthcare analytics.

## 📊 Dataset

* **File:** `Heart_disease.csv`
* Contains patient attributes such as age, sex, chest pain type, cholesterol, blood pressure, and more.
* Target variable: Presence of heart disease (binary classification).

## 🚀 Features

* Exploratory Data Analysis (EDA): missing values, summary stats, correlations
* Data visualization: heatmaps, boxplots, value counts
* Decision Tree model training & testing
* Model evaluation using accuracy and classification metrics
* Visualization of decision boundaries and feature importance

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

## 📂 Project Structure

```
├── data/
│   └── Heart_disease.csv        # Dataset
├── Decision_tree_assignment.ipynb  # Jupyter Notebook with full workflow
├── results/                     # Plots, model outputs
└── README.md                    # Project documentation
```

## ⚡ Installation

```bash
git clone <repo-url>
cd decision-tree-heart-disease
pip install -r requirements.txt
```

## ▶️ Usage

Open the notebook and run step by step:

```bash
jupyter notebook Decision_tree_assignment.ipynb
```

Or run the model training script (if converted to `.py`):

```bash
python src/train.py
```

## 📈 Results

* Decision Tree achieved strong performance on classification.
* Insights gained on important features (e.g., chest pain type, cholesterol, age).
* Tree visualization shows clear decision paths for medical predictions.

## 📈 Future Work

* Compare Decision Tree with Random Forest, XGBoost
* Hyperparameter optimization (grid search, cross-validation)
* Deploy model with Flask/Streamlit for real-time predictions

---
