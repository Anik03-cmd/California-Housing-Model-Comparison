# Feature Engineering, Model Optimization & Performance Comparison

## Table of Contents

- Project Overview
- Project Objectives
- Dataset Information
- Project Workflow
- Machine Learning Models
- Model Evaluation
- Repository Contents
- Technologies Used
- Results
- Running the Project
- Learning Outcomes
- Author
- Acknowledgement

---

# Project Overview

This project implements a complete machine learning workflow using the **California Housing Dataset** to compare the performance of multiple regression algorithms.

The project was completed as **Task 2 of the Main Crafts Technology AI & ML Internship**.

The primary objective was to perform feature engineering, train multiple regression models, evaluate their performance using standard regression metrics, and identify the best-performing model.

---

# Project Objectives

The objectives of this project are:

- Load and preprocess the California Housing Dataset.
- Apply feature scaling using StandardScaler.
- Train multiple regression models.
- Evaluate models using RMSE, MAE and R² Score.
- Compare model performance.
- Select and save the best-performing model.
- Visualize model performance using graphs.

---

# Dataset Information

| Property | Details |
|----------|---------|
| Dataset | California Housing Dataset |
| Source | Scikit-learn |
| Records | 20,640 |
| Features | 8 |
| Target Variable | Median House Value |
| Learning Type | Supervised Learning |
| Problem Type | Regression |

---

# Project Workflow

The project follows a standard machine learning workflow:

- Load the California Housing Dataset
- Perform data preprocessing
- Apply feature scaling using StandardScaler
- Split the dataset into training and testing sets
- Train multiple regression models
- Evaluate model performance
- Compare evaluation metrics
- Select the best-performing model
- Save the trained model and scaler

---

# Machine Learning Models

The following regression models were implemented:

- Linear Regression
- Ridge Regression
- Decision Tree Regressor

---

# Model Evaluation

The models were evaluated using:

| Metric | Purpose |
|---------|----------|
| RMSE | Measures prediction error magnitude |
| MAE | Measures average prediction error |
| R² Score | Measures how well the model explains the variance |

---

# Results

| Model | RMSE | MAE | R² Score |
|------|------:|------:|------:|
| Decision Tree Regressor | **0.7321** | **0.5318** | **0.6080** |
| Linear Regression | 0.7514 | 0.5400 | 0.5871 |
| Ridge Regression | 0.7514 | 0.5400 | 0.5872 |

**Best Performing Model:** Decision Tree Regressor

---

# Repository Contents

| File | Purpose |
|------|---------|
| AI_ML_Task2_Model_Comparison.ipynb | Complete notebook containing preprocessing, feature scaling, model training, evaluation, comparison and visualizations. |
| AI_ML_Task2_Report.docx | Project report describing methodology, results and conclusions. |
| model_comparison.csv | Performance comparison of all trained models. |
| best_model.pkl | Serialized best-performing model. |
| scaler.pkl | Saved StandardScaler used during preprocessing. |
| requirements.txt | Project dependencies. |

---

# Technologies Used

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | NumPy, Pandas |
| Data Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Model Serialization | Joblib |
| Development Environment | Jupyter Notebook |

---

# Visualizations

The notebook includes:

- Correlation Heatmap
- Model Performance Comparison
- Feature Importance Plot
- Actual vs Predicted Values

---

# Running the Project

Clone the repository:

```bash
git clone https://github.com/Anik03-cmd/California-Housing-Model-Comparison.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```
AI_ML_Task2_Model_Comparison.ipynb
```

Run all cells sequentially.

---

# Learning Outcomes

This project helped reinforce the following concepts:

- Feature Engineering
- Feature Scaling
- Regression Algorithms
- Model Evaluation
- Performance Comparison
- Data Visualization
- Model Optimization
- Model Serialization
- End-to-End Machine Learning Workflow

---

# Author

**Anik Biswas**

Bachelor of Technology (Computer Science and Engineering)

Amity University Kolkata

---

# Acknowledgement

This project was completed as part of the **Artificial Intelligence & Machine Learning Internship – Task 2** conducted by **Main Crafts Technology**.
