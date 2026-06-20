# 📊 Customer Churn Prediction System

A Deep Learning-based web application that predicts whether a customer is likely to leave a bank using demographic and financial information. The project leverages an Artificial Neural Network (ANN) built with TensorFlow/Keras and provides real-time churn predictions through an interactive interface.

🚀 Live Demo: [https://your-streamlit-app.streamlit.app](https://ann-mini-classification-gskeev5n4xv3pacngjtigz.streamlit.app/)

⭐ Built with TensorFlow, Keras, Scikit-learn and Streamlit.
---

## 🚀 Overview

Customer churn is a critical business problem for subscription-based and financial institutions. Acquiring new customers is often more expensive than retaining existing ones.

This project uses historical customer data to predict churn probability, enabling businesses to identify at-risk customers and take proactive retention measures.

---

## ✨ Features

* Predict customer churn using demographic and financial attributes.
* Deep Learning model built using TensorFlow and Keras.
* Real-time inference pipeline.
* Feature preprocessing with saved encoders and scalers.
* Interactive prediction interface.
* End-to-end deployment-ready workflow.

---

## 🧠 Model Architecture

The model is implemented using a feed-forward Artificial Neural Network (ANN).

```python
Dense(64, activation='relu')
Dense(32, activation='relu')
Dense(1, activation='sigmoid')
```

### Training Configuration

* Optimizer: Adam
* Loss Function: Binary Crossentropy
* Evaluation Metric: Accuracy
* Early Stopping
* TensorBoard Monitoring

---

## 📂 Dataset

Dataset: Bank Customer Churn Dataset

### Dataset Statistics

* Records: 10,000+
* Features: 14
* Target Variable: Exited

### Key Features

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Credit Card Status
* Active Member Status
* Estimated Salary

---

## 🔄 Data Preprocessing

The following preprocessing pipeline was applied:

* Removal of irrelevant identifiers
* Label Encoding
* One-Hot Encoding
* Feature Scaling using StandardScaler
* Train-Test Split

Saved preprocessing artifacts:

* geo_encoder.pkl
* gender_label.pkl
* scaler.pkl

---

## 📈 Performance

### Validation Accuracy

**~85%**

The ANN model successfully learned customer behavior patterns and achieved strong classification performance on unseen validation data.

(Add confusion matrix / training curve screenshot here)

---

## 🖥️ Application Workflow

1. User enters customer details.
2. Data is preprocessed using saved encoders and scaler.
3. Trained ANN model generates churn probability.
4. Application returns churn prediction.

---

## 📁 Project Structure

```text
ANN-mini-Classification/
│
├── app.py
├── experiment.ipynb
├── prediction.ipynb
├── model.h5
├── scaler.pkl
├── geo_encoder.pkl
├── gender_label.pkl
├── Churn_Modelling.csv
├── requirements.txt
└── README.md
```

---

## 🛠️ Tech Stack

### Machine Learning

* TensorFlow
* Keras
* Scikit-learn
* NumPy
* Pandas

### Visualization

* Matplotlib
* TensorBoard

### Deployment

* Streamlit / Flask (update based on your implementation)

### Development

* Python
* Jupyter Notebook

---

## 🔮 Future Improvements

* Hyperparameter tuning
* Explainable AI using SHAP
* Model monitoring dashboard
* Cloud deployment
* REST API integration

---

## 📚 Learning Outcomes

This project provided practical experience with:

* Deep Learning for binary classification
* Data preprocessing pipelines
* Feature engineering
* Model serialization
* Real-time inference systems
* End-to-end ML deployment workflows

---

## 👨‍💻 Author

Aditya Goswami

* LinkedIn: https://linkedin.com/in/adityaxgoswami
* GitHub: https://github.com/adityaxgoswami

```
```
