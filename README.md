# 🏡 House Price Prediction System

An end-to-end **Machine Learning web application** that predicts residential property prices across India using real-world housing data.

The project combines **data preprocessing, feature engineering, machine learning, and interactive deployment** to deliver accurate real-time house price predictions through a **Streamlit web application**.

---

# 🚀 Key Features

- 📊 Trained on 29,000+ Indian housing records
- 🤖 Machine Learning prediction using Scikit-learn
- 🧹 Automated data cleaning and preprocessing pipeline
- 📈 Feature engineering for improved prediction accuracy
- 🌍 Interactive Streamlit web application
- 📍 Supports multiple cities across India
- ⚡ Real-time property price estimation
- 📉 Visual comparison between predicted and market prices

---

# 🏗️ System Architecture

```
Housing Dataset
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
Data Preprocessing
(Imputation + Scaling + Encoding)
        │
        ▼
Linear Regression Model
        │
        ▼
Model Serialization (.pkl)
        │
        ▼
Streamlit Web Application
        │
        ▼
Real-Time House Price Prediction
```

---

# 📊 Dataset

The model was trained using a real-world Indian housing dataset containing more than **29,000 residential property listings**.

### Features

- Property Type
- BHK
- Square Footage
- RERA Status
- Under Construction
- Ready to Move
- Resale Status
- City
- Locality
- Geographic Information

Target Variable:

- House Price (Lakhs)

---

# 🛠️ Tech Stack

## Machine Learning

- Python
- Scikit-learn
- Pandas
- NumPy

## Visualization

- Matplotlib

## Deployment

- Streamlit

## Development

- VS Code
- Git
- GitHub

---

# ⚙️ Machine Learning Pipeline

The project follows an end-to-end ML workflow:

## Data Cleaning

- Removed invalid and missing records
- Handled missing values
- Removed extreme outliers
- Standardized feature formats

---

## Feature Engineering

- Extracted city and locality information
- Encoded categorical variables
- Generated additional predictive features
- Improved feature consistency

---

## Model Training

Model Used

- Linear Regression

Pipeline Components

- Simple Imputer
- Standard Scaler
- One-Hot Encoding
- Linear Regression

---

# 📈 Model Performance

| Metric | Score |
|---------|--------|
| Training R² | **0.87** |
| Validation R² | **0.74** |

The model demonstrates strong generalization while maintaining good prediction performance on unseen data.

---

# 🌐 Streamlit Application

The trained model is deployed as an interactive web application where users can

- Select city
- Enter property details
- Specify area
- Choose construction status
- Predict property prices instantly

---

# 📸 Application Preview

(Add screenshots here)

---

# 🚀 Future Improvements

- XGBoost implementation
- Random Forest comparison
- Deep Learning models
- Interactive price trend dashboard
- Map-based property visualization
- Explainable AI using SHAP
- Property recommendation engine
- Market trend forecasting

---

# 📂 Project Structure

```
House-Prediction-Final/
│
├── app.py
├── train_model.py
├── model.pkl
├── prediction.csv
├── requirements.txt
├── dataset/
├── notebooks/
└── README.md
```

---

# 🎯 Key Achievements

- Built an end-to-end Machine Learning pipeline from data preprocessing to deployment.
- Trained on 29,000+ housing records.
- Achieved an R² score of approximately **0.87 (training)** and **0.74 (validation)**.
- Developed an interactive Streamlit interface for real-time house price prediction.
- Applied feature engineering and preprocessing techniques to improve model performance.

---

# 🔗 Live Demo

(Add your Streamlit URL)

---

# 📄 License

This project is intended for educational and learning purposes.
