# ✨ Project 7: Improving Models with Feature Engineering

## 🎯 Objective
To demonstrate the power of feature engineering by creating new, more informative features from the Titanic dataset and showing a quantifiable improvement in model performance.

## 📖 Topic Introduction
**What is Feature Engineering?**
Feature Engineering is the process of using domain knowledge to create new features (input variables) from raw data. It's often the most creative part of machine learning and can have a greater impact on model performance than the choice of algorithm itself. It involves transforming raw data into a format that better represents the underlying problem to the predictive models.

## 📊 Dataset
- **Source:** [Kaggle's Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

## 🛠️ Tech Stack
- Python, Pandas, Scikit-learn

## 📈 Workflow
1.  **Baseline Model:** Trained a Random Forest classifier on basic features to establish a baseline accuracy.
2.  **Feature Engineering:** Created `FamilySize`, `IsAlone`, and `Title` features.
3.  **New Model:** Trained a new model on the enhanced dataset and compared its accuracy to the baseline.

## ✨ Key Results
- **Accuracy Boost:** The model's accuracy improved from **~80.2%** (baseline) to **~83.2%** with the new features, a relative improvement of **3.7%**.

![Model Improvement Chart](model_improvement_chart.png)

## 📚 Resources
- **Article:** [A Practical Guide to Feature Engineering](https://www.freecodecamp.org/news/a-practical-guide-to-feature-engineering-in-python/)
- **Documentation:** [Feature Engineering with Scikit-learn](https://scikit-learn.org/stable/modules/preprocessing.html)
