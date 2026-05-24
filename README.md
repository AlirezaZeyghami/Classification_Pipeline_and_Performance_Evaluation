# Breast Cancer Classification Pipeline and Performance Evaluation

Machine Learning classification pipeline project using the Breast Cancer Wisconsin Dataset from scikit-learn.

This project was developed as part of the ARI5003 Machine Learning course assignment and focuses on building, evaluating, and analyzing multiple machine learning classification models for medical diagnosis.

---

# Project Objectives

The primary goals of this project are:

- Build a complete machine learning classification pipeline
- Apply preprocessing and feature scaling techniques
- Train and compare multiple classifiers
- Analyze classification performance using evaluation metrics
- Investigate overfitting and underfitting behavior
- Evaluate generalization capability using cross-validation
- Interpret confusion matrices and medical classification risks

---

# Dataset

This project uses the Breast Cancer Wisconsin Dataset available in scikit-learn.

Dataset characteristics:

- 569 samples
- 30 numerical features
- Binary classification problem:
  - Malignant
  - Benign

The dataset contains numerical features extracted from digitized images of breast mass cell nuclei.

Official dataset documentation:

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html

---

# Technologies and Libraries

- Python
- Google Colab
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

---

# Machine Learning Models

The following classifiers were implemented and evaluated:

## 1. Logistic Regression

- Linear classification algorithm
- Sensitive to feature scaling
- Strong generalization capability

## 2. k-Nearest Neighbors (kNN)

- Distance-based classifier
- Sensitive to feature scaling
- Hyperparameter tuning using different k values

## 3. Decision Tree

- Tree-based classification algorithm
- Interpretable decision-making structure
- Model complexity analysis using different tree depths

---

# Project Workflow

The project includes the following stages:

1. Dataset exploration
2. Missing value analysis
3. Feature scaling using StandardScaler
4. Train-test split (80%-20%)
5. Logistic Regression training
6. kNN training and hyperparameter analysis
7. Decision Tree training and depth analysis
8. Performance evaluation
9. Confusion matrix analysis
10. Cross-validation
11. Overfitting and underfitting investigation
12. Final comparison and interpretation

---

# Evaluation Metrics

The classifiers were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- Cross-validation accuracy

---

# Key Concepts Explored

This project investigates several important machine learning concepts:

- Classification pipelines
- Feature scaling
- Data preprocessing
- Model evaluation
- Cross-validation
- Generalization performance
- Bias-variance tradeoff
- Overfitting vs underfitting
- Medical AI evaluation challenges

---

# Medical Interpretation

In medical diagnosis tasks, Accuracy alone is not sufficient.

Special attention must be given to:

- Recall
- False Negatives
- F1-score

Because incorrectly classifying malignant tumors as benign may delay treatment and create serious medical risks.

---

# Results Summary

Main findings from the experiments:

- Logistic Regression achieved strong and stable overall performance
- kNN performance was highly affected by the choice of k value
- Decision Trees showed overfitting behavior with excessive depth
- Feature scaling significantly improved kNN and Logistic Regression performance
- Cross-validation confirmed stable model generalization

---

# Final Conclusion

Among all evaluated classifiers, Logistic Regression provided the best balance between:

- accuracy
- simplicity
- computational efficiency
- interpretability
- generalization capability

This project demonstrates how preprocessing, feature scaling, model complexity, and evaluation strategies affect machine learning classification performance.

---

# Repository Structure

```bash
.
├── ARI5003_HW2_Classification_Pipeline.ipynb
├── HW2_Report.pdf
├── README.md
└── images/

```markdown
Author
Alireza Z.
Product-Oriented Technologist
