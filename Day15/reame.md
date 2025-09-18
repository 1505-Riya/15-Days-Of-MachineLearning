# 🚀 Project 15: Deploying an ML Model with FastAPI

## 🎯 Objective
To deploy the Iris classification model as a live REST API using FastAPI, representing the final step in the ML lifecycle: making a model accessible for real-world use.

## 📖 Topic Introduction
**What is Model Deployment?**
Model deployment is the process of integrating a machine learning model into an existing production environment to make practical business decisions based on data. An **API (Application Programming Interface)** is a standard way to make a model's predictions available to other applications (like websites or mobile apps).
- **FastAPI:** A modern, high-performance Python web framework for building APIs. It's known for its speed, ease of use, and automatic interactive documentation.
- **Serialization:** The process of saving a trained model to a file (`joblib` or `pickle`) so it can be loaded into an application without retraining.

## 📦 Model
- **Source:** A `LogisticRegression` model trained on the Scikit-learn Iris dataset.
- **Serialization:** Saved to a file (`iris_model.joblib`) using `joblib`.

## 🛠️ Tech Stack
- Python, FastAPI, Uvicorn, Scikit-learn, Joblib, Pydantic

## 🏗️ Architecture
1.  **`train_and_save_model.py`:** A script to train the model and serialize it.
2.  **`main.py`:** The FastAPI application that loads the model and defines a `/predict` endpoint.
3.  **Uvicorn:** An ASGI server used to run the live FastAPI application.

## ✨ Key Results
- **Live Endpoint:** The API runs locally and can serve predictions in real-time.
- **Interactive Documentation:** FastAPI automatically generates a user-friendly Swagger UI for easy testing and interaction.

![FastAPI Interactive Docs](api_docs.png)

## 🚀 How to Run
1.  Clone the repository.
2.  Install required libraries: `pip install fastapi "uvicorn[standard]" scikit-learn joblib pandas`
3.  First, train and save the model: `python train_and_save_model.py`
4.  Then, start the live API server: `uvicorn main:app --reload`
5.  Open your browser to `http://12.0.0.1:8000/docs` to interact with the API.

## 📚 Resources
- **Video:** [freeCodeCamp: FastAPI Course for Beginners](https://www.youtube.com/watch?v=7t2alSnE2-I)
- **Documentation:** [FastAPI Official Tutorial](https://fastapi.tiangolo.com/tutorial/)
