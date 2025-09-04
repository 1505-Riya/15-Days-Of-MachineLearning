# 🌸 Project 4: Iris Flower Classification

## 🎯 Objective
To build a multi-class classification model using Logistic Regression to predict the species of an Iris flower.

## 📖 Topic Introduction
**What is Logistic Regression?**
Despite its name, Logistic Regression is a powerful and fundamental algorithm for **classification**, not regression. It models the probability that a given input point belongs to a certain class. It works by passing the weighted sum of inputs through a sigmoid function, which squashes the output to a probability between 0 and 1.

## 📊 Dataset
- **Source:** Built-in Scikit-learn `load_iris` dataset.
- **Description:** A classic dataset containing 150 samples of Iris flowers.

## 🛠️ Tech Stack
- Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## 📈 Workflow
1.  **Data Loading & EDA:** Loaded the dataset and created a `pairplot` to visualize class separability.
2.  **Model Training:** Trained a `LogisticRegression` model.
3.  **Model Evaluation:** Evaluated performance using an accuracy score and a confusion matrix.

## ✨ Key Results
- **Accuracy:** Achieved **100% accuracy** on the unseen test data.
- **Confusion Matrix:** Showed zero misclassifications.

![Confusion Matrix](confusion_matrix.png)

## 📚 Resources
- **Video:** [StatQuest: Logistic Regression](https://www.youtube.com/watch?v=yIYKR4sgzI8)
- **Documentation:** [Scikit-learn: LogisticRegression](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html)
