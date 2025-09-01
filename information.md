# 🚀 15 Days of Machine Learning: A Project-Based Journey

Welcome to my 15-Day Machine Learning Challenge! This repository documents a daily commitment to building and understanding a new machine learning concept, starting from fundamental data analysis and culminating in a fully deployed model. Each project is self-contained, with its own dataset and clear objective.

This challenge was undertaken to build a practical, hands-on portfolio demonstrating an end-to-end data science workflow.

---

##  Project List

### 📊 Week 1: Foundations of Data Science & Core Models

#### **Day 1: Exploratory Data Analysis (EDA)**
* **Objective:** To analyze the classic Titanic dataset to find key factors that influenced passenger survival using data cleaning, visualization, and storytelling.
* **Dataset:** [Kaggle's Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

#### **Day 2: Simple Linear Regression**
* **Objective:** To build a basic predictive model to predict a student's percentage score based on the number of hours they studied.
* **Dataset:** [Student Study Hour to Score Prediction on Kaggle](https://www.kaggle.com/datasets/karthickaraveti/simple-linear-regression-data)

#### **Day 3: Multiple Linear Regression**
* **Objective:** To predict Boston house prices using multiple features (crime rate, number of rooms, etc.) and to interpret which factors are most important.
* **Dataset:** The user-provided `HousingData.csv`, a version of the Boston Housing dataset. A similar version can be found [here on Kaggle](https://www.kaggle.com/datasets/altavish/boston-housing-dataset).

#### **Day 4: Logistic Regression (Classification)**
* **Objective:** To build a multi-class classification model to predict the species of an Iris flower based on its sepal and petal measurements.
* **Dataset:** Built into Scikit-learn. Loaded via `sklearn.datasets.load_iris`.

#### **Day 5: Decision Trees & Random Forest**
* **Objective:** To predict customer churn for a telecom company, introducing more powerful, tree-based ensemble models and handling categorical data.
* **Dataset:** [Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

### 🧠 Week 2: Deeper Concepts & Unsupervised Learning

#### **Day 6: Advanced Model Evaluation**
* **Objective:** To go beyond simple accuracy by evaluating the churn model with Precision, Recall, F1-Score, and the ROC/AUC curve to understand its true business impact.
* **Dataset:** [Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

#### **Day 7: Feature Engineering**
* **Objective:** To improve a model's performance by creatively engineering new, more informative features from the existing Titanic data.
* **Dataset:** [Kaggle's Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)

#### **Day 8: K-Means Clustering**
* **Objective:** To perform unsupervised learning by segmenting mall customers into distinct groups based on their spending habits, without any pre-existing labels.
* **Dataset:** [Mall Customer Segmentation Data on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

#### **Day 9: Principal Component Analysis (PCA)**
* **Objective:** To introduce dimensionality reduction by compressing a high-dimensional dataset of handwritten digits (64 features) down to just 2 for visualization.
* **Dataset:** Built into Scikit-learn. Loaded via `sklearn.datasets.load_digits`.

#### **Day 10: Sentiment Analysis (NLP)**
* **Objective:** To build a sentiment analysis classifier to determine if a movie review is positive or negative, introducing the fundamentals of Natural Language Processing.
* **Dataset:** [IMDb Dataset of 50K Movie Reviews on Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

---

### 🤖 Week 3: Advanced Applications & Deployment

#### **Day 11: Topic Modeling (NLP)**
* **Objective:** To use Latent Dirichlet Allocation (LDA) to automatically discover hidden topics from a large collection of news articles without any prior labels.
* **Dataset:** Built into Scikit-learn. Loaded via `sklearn.datasets.fetch_20newsgroups`.

#### **Day 12: Image Classification with a CNN**
* **Objective:** To build a Convolutional Neural Network (CNN) from scratch to classify small color images from the CIFAR-10 dataset into 10 categories.
* **Dataset:** Built into TensorFlow/Keras. Loaded via `tensorflow.keras.datasets.cifar10`.

#### **Day 13: Object Detection with YOLO**
* **Objective:** To use a state-of-the-art, pre-trained YOLOv5 model to perform object detection, drawing bounding boxes around objects in a custom image.
* **Dataset:** No training dataset required. The model is pre-trained on the **COCO dataset** and loaded via PyTorch Hub.

#### **Day 14: Time Series Forecasting**
* **Objective:** To build a forecasting model using the ARIMA method to predict future monthly airline passenger numbers based on historical data.
* **Dataset:** [Air Passengers Dataset on Kaggle](https://www.kaggle.com/datasets/rakannimer/air-passengers)

#### **Day 15: Model Deployment with an API**
* **Objective:** To deploy the Iris classification model as a live REST API using FastAPI, making it accessible for real-world applications.
* **Model/Dataset:** Uses
