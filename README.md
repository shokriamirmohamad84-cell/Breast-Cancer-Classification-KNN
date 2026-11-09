# Breast Cancer Classification Using K-Nearest Neighbors (KNN)

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikitlearn)
![Status](https://img.shields.io/badge/Status-Completed-success)

## Overview

This project implements a Machine Learning classification model using the **K-Nearest Neighbors (KNN)** algorithm to classify breast tumors as **Benign** or **Malignant**.

The main objective is to evaluate different K values and identify a suitable number of neighbors for accurate classification.

## Dataset

The project uses the **Breast Cancer Wisconsin Diagnostic Dataset**.

- Samples: 569
- Features: 30 numerical features
- Target: Binary classification
  - `0` – Benign
  - `1` – Malignant

The features describe characteristics of cell nuclei, including radius, texture, perimeter, area, smoothness, and other measurements.

## Technologies & Libraries

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Import Libraries
Import the required libraries for data analysis, visualization, preprocessing, and machine learning.

### 2. Data Loading & Exploration
Load the dataset using Pandas and explore its structure, features, and class distribution.

### 3. Data Preprocessing
Separate input features (`X`) from target labels (`y`) and apply feature scaling using `StandardScaler`.

### 4. Train-Test Split
Split the dataset into training and testing sets to evaluate the model on unseen data.

### 5. KNN Model Training
Train the KNN classifier using different values of K, from 1 to 9.

### 6. Model Evaluation
Evaluate model performance using the Accuracy Score metric.

### 7. Optimal K Selection
Compare the accuracy scores for different K values to identify the best-performing configuration.

### 8. Data Visualization
Visualize the accuracy results using Matplotlib to understand how the number of neighbors affects model performance.

## Model Evaluation

The model is evaluated using:

- **Accuracy Score:** Measures the proportion of correct predictions.
- **Train Accuracy:** Evaluates performance on training data.
- **Test Accuracy:** Evaluates performance on unseen testing data.

The best K value is selected based on the accuracy comparison.

## Project Structure

```text
Breast-Cancer-Classification-KNN/
│
├── Breast_Cancer_KNN.ipynb
├── breast_cancer_wisconsin_real.csv
└── README.md
```

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/YOUR-USERNAME/Breast-Cancer-Classification-KNN.git
```

2. Navigate to the project directory:

```bash
cd Breast-Cancer-Classification-KNN
```

3. Install the required libraries:

```bash
pip install numpy pandas matplotlib scikit-learn jupyter
```

4. Open Jupyter Notebook:

```bash
jupyter notebook
```

5. Open and run `Breast_Cancer_KNN.ipynb`.

## Learning Objectives

Through this project, I practiced:

- Data preprocessing and feature scaling.
- Training classification models with Scikit-learn.
- Understanding the K-Nearest Neighbors algorithm.
- Evaluating machine learning models.
- Comparing model performance using different K values.
- Visualizing model accuracy.

## Disclaimer

This project is for educational purposes only and is not intended for medical diagnosis.

---

**Author:** Amir Shokri  
**Project:** Machine Learning – KNN Classification  
**GitHub:** YOUR-GITHUB-USERNAME
