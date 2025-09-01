# 🚢 Project 1: Titanic Survival Analysis (EDA)

## 🎯 Objective
The goal of this project is to perform an in-depth Exploratory Data Analysis (EDA) on the classic Titanic dataset. The analysis aims to uncover key factors that influenced passenger survival and to tell a story using data visualization.

## 📊 Dataset
- **Source:** [Kaggle's Titanic - Machine Learning from Disaster](https://www.kaggle.com/c/titanic)
- **Description:** The dataset contains passenger information (age, gender, class, etc.) and whether they survived the sinking of the Titanic.

## 🛠️ Tech Stack
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

## 📈 Workflow
1.  **Data Loading & Cleaning:** Loaded the `train.csv` file, handled missing values in `Age` and `Embarked` columns.
2.  **Exploratory Data Analysis (EDA):** Investigated the relationships between survival and key features like gender, passenger class, age, and family size.
3.  **Visualization:** Created several plots, including count plots, histograms, and a correlation heatmap to visualize the findings.

## ✨ Key Results & Visuals
The analysis revealed several key insights:
- **Gender:** Women had a significantly higher survival rate (~74%) compared to men (~19%).
- **Passenger Class:** 1st class passengers had the highest survival rate (~63%), while 3rd class had the lowest (~24%).
- **Age:** Children had a higher chance of survival than adults.

![Titanic Survival by Class](pclass_survival.png)

## 🚀 How to Run
1. Clone the repository.
2. Install the required libraries: `pip install pandas matplotlib seaborn`
3. Run the Jupyter Notebook or Python script `titanic_eda.py`.
