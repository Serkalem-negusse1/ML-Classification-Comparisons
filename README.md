# ML-Classification-Comparisons

This repository demonstrates and compares three popular **supervised classification algorithms**: **Logistic Regression (LR)**, **K-Nearest Neighbors (KNN)**, and **Support Vector Machine (SVM)**. The project uses datasets like the **Diabetes dataset** and **Pulsar Stars dataset** to evaluate model performance using various metrics.

---

## **Table of Contents**

- [Overview](#overview)  
- [Datasets](#datasets)  
- [Implemented Models](#implemented-models)  
- [Evaluation Metrics](#evaluation-metrics)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Results](#results)  
- [Contributing](#contributing)  
- [License](#license)  

---

## **Overview**

This project explores:

- Logistic Regression (LR) – a linear probabilistic model  
- K-Nearest Neighbors (KNN) – an instance-based non-parametric model  
- Support Vector Machine (SVM) – a margin-based classifier with kernel support  

It demonstrates **training, testing, hyperparameter tuning**, and **evaluation** using metrics like accuracy, confusion matrix, and ROC-AUC.

---

## **Datasets**

1. **Diabetes Dataset** – Binary classification predicting diabetes onset.  
2. **Pulsar Stars Dataset** – Binary classification for pulsar star detection.  

Datasets are loaded using **scikit-learn** or downloaded as CSV files.

---

## **Implemented Models**

- **Logistic Regression**  
  - Linear model with optional regularization (L1/L2)  
  - Outputs probabilities  
- **K-Nearest Neighbors (KNN)**  
  - Distance-based classification  
  - Hyperparameters: `k`, `weights`, `distance metric`  
- **Support Vector Machine (SVM)**  
  - Linear and non-linear kernels (linear, RBF, polynomial)  
  - Hyperparameters: `C`, `kernel`, `gamma`  

All models include **scaling, hyperparameter tuning with GridSearchCV**, and evaluation.

---

## **Evaluation Metrics**

- **Accuracy** – Correct predictions ratio  
- **Classification Report** – Precision, recall, F1-score  
- **Confusion Matrix** – TP, FP, TN, FN visualization  
- **ROC-AUC** – Performance across thresholds  

---

## **Installation**

```bash
git clone https://github.com/Serkalem-negusse1/ML-Classification-Comparisons.git
cd ML-Classification-Comparisons
pip install -r requirements.txt
