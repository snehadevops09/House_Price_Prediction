# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview
This project focuses on predicting house prices based on various features such as area, number of bedrooms, bathrooms, and other property attributes. The model is built using Linear Regression and demonstrates a complete machine learning workflow including data preprocessing, feature engineering, model training, and evaluation.

---

## 🎯 Objectives
- Analyze housing data to identify key factors affecting price
- Perform data preprocessing and feature encoding
- Build and train a Linear Regression model
- Evaluate model performance using appropriate metrics
- Visualize relationships and model predictions

---

## 📊 Dataset Description
The dataset contains multiple features related to house properties:

- **Price** – Target variable  
- **Area** – Size of the house  
- **Bedrooms, Bathrooms, Stories** – Structural details  
- **Mainroad, Guestroom, Basement, Airconditioning, Prefarea** – Binary features  
- **Parking** – Number of parking spaces  
- **Furnishing Status** – Categorical feature  

---

## 🛠️ Technologies & Libraries Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## ⚙️ Project Workflow

### 1. Data Preprocessing
- Handling missing values  
- Converting categorical variables (Yes/No → 1/0)  
- One-hot encoding for multi-category features  

### 2. Exploratory Data Analysis (EDA)
- Correlation heatmap  
- Feature relationships visualization  
- Distribution analysis  

### 3. Model Building
- Train-test split (80/20)  
- Linear Regression model training  

### 4. Model Evaluation
- Mean Squared Error (MSE)  
- R² Score  
- Residual analysis  

### 5. Visualization
- Heatmap of correlations  
- Actual vs Predicted scatter plot  
- Feature importance analysis  

---

## 📈 Results & Insights
- **Area** has the strongest influence on house price  
- Features like **bathrooms and parking** show moderate impact  
- Model achieves good performance based on R² score  
- Predictions closely align with actual values  
