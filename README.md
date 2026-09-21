# Textile Production Forecasting Using Machine Learning

## 📌 Project Overview

This project focuses on applying machine learning techniques to **textile production forecasting**. The objective is to analyze production-related data and compare different machine learning algorithms to identify models capable of producing accurate predictions.

Textile production involves multiple interacting variables, making machine learning useful for identifying patterns within historical production data and supporting forecasting, resource allocation, inventory management, and operational planning.

The project performs data preprocessing, feature preparation, model training, prediction, evaluation, and comparison of multiple machine learning algorithms.

---

## 🎯 Objectives

* Analyze textile production data.
* Preprocess and prepare the dataset for machine learning.
* Apply different machine learning algorithms.
* Compare model performance.
* Evaluate prediction accuracy.
* Identify models that provide effective predictive performance for textile production.
* Visualize and analyze the obtained results.

---

# 🤖 Machine Learning Algorithms Used

The project investigates multiple machine learning algorithms for textile production prediction.

### 1. XGBoost

**XGBoost (Extreme Gradient Boosting)** is a gradient boosting algorithm that builds multiple decision trees sequentially, with each new tree attempting to improve the errors made by previous trees.

It was used as one of the primary algorithms for textile production prediction and was compared against several other machine learning approaches.

---

### 2. Support Vector Machine (SVM)

Support Vector Machine is a supervised machine learning algorithm that identifies an optimal decision boundary between data points.

In the uploaded analysis, SVM was evaluated against XGBoost for textile production forecasting.

**Reported accuracy:**

* SVM: **91.859%**
* XGBoost: **68.386%**

The presentation reports SVM as having higher accuracy in this comparison.

---

### 3. Random Forest

Random Forest is an ensemble learning algorithm that combines predictions from multiple decision trees to produce a final prediction.

The project compared Random Forest with XGBoost.

**Reported mean accuracy:**

| Algorithm     | Accuracy |
| ------------- | -------: |
| Random Forest |   61.18% |
| XGBoost       |   63.38% |

The corresponding analysis reports XGBoost with a higher mean accuracy than Random Forest in this experiment.

---

### 4. Decision Tree

Decision Tree is a supervised learning algorithm that makes predictions through a sequence of decision rules.

The project compared Decision Tree with XGBoost.

**Reported mean accuracy:**

| Algorithm     | Accuracy |
| ------------- | -------: |
| Decision Tree |  57.947% |
| XGBoost       |  68.386% |

The analysis reports higher accuracy for XGBoost in this comparison.

---

### 5. Logistic Regression

Logistic Regression was also investigated as a machine learning approach for textile production-related prediction.

The uploaded analysis reports:

| Algorithm           | Reported Accuracy |
| ------------------- | ----------------: |
| Logistic Regression |            87.00% |
| XGBoost             |            68.38% |

The analysis discusses Logistic Regression as a comparatively interpretable model for the evaluated task.

---

# 📊 Model Comparison

The project contains multiple comparative experiments between machine learning algorithms.

| Comparison   | Model 1             | Model 2       | Reported Result                                      |
| ------------ | ------------------- | ------------- | ---------------------------------------------------- |
| Experiment 1 | XGBoost             | Decision Tree | XGBoost: **68.386%**, Decision Tree: **57.947%**     |
| Experiment 2 | XGBoost             | Random Forest | XGBoost: **63.38%**, Random Forest: **61.18%**       |
| Experiment 3 | SVM                 | XGBoost       | SVM: **91.859%**, XGBoost: **68.386%**               |
| Experiment 4 | Logistic Regression | XGBoost       | Logistic Regression: **87.00%**, XGBoost: **68.38%** |

## The reported values come from separate comparative analyses in the project material and should therefore be interpreted as experiment-specific results rather than one unified leaderboard.

# 📈 Outputs

The project generates algorithm-performance comparisons and prediction-related visualizations.

The uploaded presentations contain graphs showing:

* Algorithm accuracy comparison
* XGBoost vs Decision Tree
* XGBoost vs Random Forest
* XGBoost vs Support Vector Machine
* Algorithm statistics
* Textile production prediction

## The statistical analysis also includes mean accuracy, standard deviation, and standard error values for the evaluated models.

# 🔬 Methodology

The overall machine learning workflow used in the project can be summarized as:

```text
Raw Data
    ↓
Data Retrieval
    ↓
Data Preprocessing
    ↓
Data Formatting / Transformation
    ↓
Feature Engineering
    ↓
Feature Selection / Scaling
    ↓
Training Dataset
    ↓
Testing Dataset
    ↓
Machine Learning Algorithms
    ↓
Model Training
    ↓
Model Evaluation
    ↓
Prediction
    ↓
Performance Comparison
```

The uploaded project materials describe stages including data retrieval, preprocessing, feature extraction/engineering, feature selection/scaling, model training, evaluation and tuning, prediction, and deployment/monitoring.

---

# 📊 Statistical Analysis

Statistical analysis was performed using **IBM SPSS** to analyze the results obtained from the machine learning models.

The presentations report independent-sample T-test analyses as part of the comparison between algorithms.

---

# 🏆 Key Findings

The experiments demonstrate that model performance varies depending on the algorithm and comparison being evaluated.

* **XGBoost vs Decision Tree:** XGBoost achieved a reported accuracy of **68.386%**, compared with **57.947%** for Decision Tree.
* **XGBoost vs Random Forest:** XGBoost achieved **63.38%**, compared with **61.18%** for Random Forest.
* **SVM vs XGBoost:** SVM achieved a reported **91.859%**, compared with **68.386%** for XGBoost.
* **Logistic Regression vs XGBoost:** the analysis reports **87.00%** for Logistic Regression and **68.38%** for XGBoost.

These results demonstrate the importance of evaluating multiple algorithms rather than assuming that a single model will perform best for every textile production dataset.

---

# ✅ Conclusion

This project demonstrates the application of machine learning to textile production forecasting through comparative evaluation of multiple algorithms.

The experiments included **XGBoost, Decision Tree, Random Forest, Support Vector Machine, and Logistic Regression**. The results show that predictive performance varies significantly between algorithms and experimental comparisons.

The project highlights the importance of **data preprocessing, feature engineering, algorithm selection, model evaluation, and statistical analysis** when developing machine learning solutions for production forecasting.

The comparative approach provides a foundation for selecting appropriate machine learning techniques for textile production prediction and can be further improved through larger datasets, hyperparameter optimization, additional production variables, and more robust validation techniques.

---

# 🛠️ Technologies & Tools

* Python
* Machine Learning
* XGBoost
* Scikit-learn
* Pandas
* NumPy
* Matplotlib
* IBM SPSS
* Jupyter Notebook

---

# 📂 Project Workflow

```text
Textile Production Data
        ↓
Data Preprocessing
        ↓
Feature Engineering
        ↓
Model Training
        ↓
XGBoost
Decision Tree
Random Forest
SVM
Logistic Regression
        ↓
Model Evaluation
        ↓
Accuracy Comparison
        ↓
Textile Production Prediction
```

---

# 👨‍💻 Author

**S. Ashish Kumar**

B.Tech – Artificial Intelligence & Data Science

**Project:** Textile Production Forecasting Using Machine Learning
