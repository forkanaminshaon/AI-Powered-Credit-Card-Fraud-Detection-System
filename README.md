# 💳 AI-Powered Credit Card Fraud Detection System

An end-to-end **Machine Learning project** that detects fraudulent credit card transactions and deploys the model as an **interactive web application using Streamlit**.

This project demonstrates how machine learning can help financial institutions identify suspicious transactions and prevent fraud in real time.

---

# Project Overview

Credit card fraud is a major challenge in the financial industry. Fraudulent transactions are rare compared to legitimate ones, making the dataset **highly imbalanced**.

This project builds a **fraud detection system using machine learning** to classify whether a transaction is **fraudulent or legitimate**.

The system includes:

- Data preprocessing and feature engineering  
- Handling class imbalance using **SMOTE**  
- Training a **LightGBM machine learning model**  
- Model evaluation using multiple metrics  
- Deployment using **Streamlit Web App**

---

# Machine Learning Workflow

Data Collection
↓
Data Cleaning & Preprocessing
↓
Feature Engineering
↓
Handling Imbalanced Data (SMOTE)
↓
Model Training (LightGBM)
↓
Model Evaluation
↓
Model Saving (Joblib)
↓
Web App Deployment (Streamlit)


---

# Features

✔ Fraud transaction detection using **Machine Learning**  
✔ Handles **highly imbalanced datasets** using SMOTE  
✔ Uses **LightGBM gradient boosting algorithm**  
✔ Calculates **geographical transaction distance using Geopy**  
✔ Visualizes model insights using **Matplotlib & Seaborn**  
✔ Deploys the model as a **real-time Streamlit web application**

---

# 📂 Project Structure

AI-Powered-Credit-Card-Fraud-Detection-System
│
├── app.py
├── fraud_detection_model.jb
├── label_encoder.jb
├── requirements.txt
├── README.md


---

# ⚙️ Installation

Clone the repository:

git clone https://github.com/forkanaminshaon/AI-Powered-Credit-Card-Fraud-Detection-System.git


Navigate to the project folder:

cd AI-Powered-Credit-Card-Fraud-Detection-System

Install dependencies:

pip install -r requirements.txt


---

# ▶️ Run the Streamlit App

Run the following command:

streamlit run app.py


The application will open in your browser.

---

# Model Evaluation Metrics

The model performance is evaluated using:

- Precision
- Recall
- F1 Score
- ROC AUC Score
- Confusion Matrix

These metrics help determine how well the model detects fraudulent transactions.

---

# Machine Learning Techniques Used

### Data Processing
- Handling missing values
- Feature engineering
- Date-time feature extraction

### Handling Imbalanced Data
- **SMOTE (Synthetic Minority Oversampling Technique)**

### Model
- **LightGBM Classifier**

### Visualization
- Feature Importance
- ROC Curve
- Class Distribution

---

# 🛠 Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- LightGBM  
- Matplotlib  
- Seaborn  
- Streamlit  
- Geopy  
- Imbalanced-learn (SMOTE)  
- Joblib  

---

# Use Cases

- Banking fraud detection  
- Financial transaction monitoring  
- Risk management systems  
- Real-time fraud detection platforms  

---

# Future Improvements

- Add **Deep Learning models**  
- Implement **real-time transaction API**  
- Deploy on **Streamlit Cloud / AWS**  
- Add **dashboard analytics**

---

# Author

**Forkan Amin**

Applied Mathematics Graduate  
Machine Learning & Data Science Enthusiast

GitHub:  
https://github.com/forkanaminshaon

---

⭐ If you like this project, consider giving it a **star on GitHub!**
