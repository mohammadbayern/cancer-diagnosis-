# 🔬 Cancer Diagnosis using Machine Learning

## 📌 Project Overview
This project focuses on **cancer diagnosis prediction** using classical machine learning techniques applied to structured medical data.  
The objective is to classify tumors as **benign or malignant** based on diagnostic measurements, demonstrating a complete and reproducible **data science workflow**.

This project is designed as a **portfolio-grade, dual-purpose project**, suitable for:
- Master’s degree applications
- Research-oriented academic programs
- Data Science / Machine Learning internships and junior roles

---

## 📊 Dataset Description
The dataset contains numerical features extracted from medical diagnostic examinations.

**Target variable:**
- Cancer diagnosis (Benign / Malignant)

**Feature categories include:**
- Radius, texture, perimeter, area
- Smoothness and compactness
- Concavity, concave points, symmetry

All features are numerical and suitable for classical machine learning models.

---

## 🔍 Exploratory Data Analysis (EDA)
Exploratory analysis was conducted to understand feature distributions and relationships.

Key insights:
- Strong correlation between size-related features and malignancy
- Certain texture and concavity features show high discriminative power
- The dataset is well-structured and suitable for binary classification

EDA helped guide model selection and preprocessing decisions.

---

## 🧠 Machine Learning Workflow
The following steps were implemented in the notebook:

- Data loading and cleaning
- Feature-target separation
- Train-test split with stratification
- Feature scaling using StandardScaler
- Training multiple classification models
- Model evaluation and comparison

This workflow ensures **clarity, reproducibility, and scalability**.

---

## 📊 Model Comparison & Evaluation
Three classification models were trained and evaluated:

- Logistic Regression (baseline)
- Support Vector Machine (RBF kernel)
- Random Forest Classifier

**Evaluation metrics:**
- Accuracy
- Precision, Recall, F1-score
- Confusion Matrix
- ROC Curve & AUC

Among the tested models, **Random Forest achieved the highest overall performance and robustness**, making it the most reliable classifier for this dataset.

---

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Kaggle Notebook

---

## 🎯 Why This Project Matters
This project demonstrates:
- Practical application of machine learning in healthcare
- Strong understanding of exploratory data analysis
- Proper use of evaluation metrics for classification problems
- Ability to build clean, reproducible ML pipelines

It reflects both **academic readiness** and **industry-oriented problem solving**.

---

## 🚀 Future Improvements
- Hyperparameter tuning and cross-validation
- Feature selection and dimensionality reduction
- Comparison with additional models
- Deployment-ready pipeline preparation

---

## 👤 Author
**Mohamad Nahvi**  
Aspiring Data Scientist | Machine Learning Enthusiast  





📁 Cancer Diagnosis Dataset
📌 Dataset Overview

This dataset contains medical diagnostic measurements used for cancer diagnosis classification tasks.
Each row represents a patient sample, and each column corresponds to a quantitative feature extracted from medical examinations.

The dataset is suitable for:

Binary classification

Medical data analysis

Feature importance studies

Machine learning benchmarking

📊 File Information

File name: cancer.csv

Format: CSV

Rows: Patient samples

Columns: Numeric diagnostic features + target label

🧾 Column Description

Diagnosis / Target:

0 → Benign

1 → Malignant

Feature Columns:
Numeric measurements related to:

Tumor size

Shape irregularity

Texture and smoothness

Compactness and concavity

All features are continuous and normalized-ready.

🔐 Data Usage

No personal or identifiable patient information included

Intended for educational and research purposes only

Suitable for academic projects and ML experimentation

🛠️ Recommended Use Cases

Binary classification models

Feature selection and importance analysis

Healthcare-focused ML demonstrations

Academic coursework and portfolio projects

📜 License

This dataset is shared for educational and research purposes.

Please cite the repository if used in academic or professional work.
