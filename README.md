# 🌍 CO₂ Emissions Forecasting Using Machine Learning

## 👨‍🎓 Student Details

- **Name**: Mustafa Kasubhaiwala  
- AICTE Student ID: STU68343691dfff41748252305


---

## 📌 Project Overview

This project focuses on forecasting **CO₂ emissions per capita** using **Machine Learning (Random Forest Regressor)** based on socio-economic and environmental indicators. It aims to support data-driven climate action by predicting emissions for different countries over the next 20 years, enabling policymakers to plan for a sustainable future.

---

## 🎯 Learning Objectives

- Understand different Python libraries for data analysis and machine learning  
- Learn preprocessing and feature engineering techniques  
- Build and train a machine learning model (Random Forest Regressor)  
- Apply Cross-Validation and Hyperparameter Tuning  
- Calculate **CAGR (Compound Annual Growth Rate)** for selected indicators  
- Forecast CO₂ emissions using predicted feature values  
- Visualize trends and draw actionable insights

---

## 🛠️ Tools & Technologies Used

- **Language**: Python 3.12  
- **Environment**: Jupyter Notebook  
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Visualization
  - `scikit-learn` – ML model, metrics, CV
  - `joblib` – Model saving/loading  
- **Data Format**: CSV  
- **Version Control**: Git 

---

## 🧩 Problem Statement

> **How might we** forecast CO₂ emissions per capita for different countries using data-driven techniques, so that governments and organizations can proactively plan for climate change and sustainability goals?

As industrialization and urbanization grow globally, especially in developing countries, CO₂ emissions continue to rise. Predicting future emissions is essential for setting climate targets  but is challenging due to complex, interdependent factors like energy usage, economic growth, and population dynamics.

---

## 💡 Solution Approach

We developed a machine learning pipeline using **Random Forest Regressor** to predict future CO₂ emissions per capita. Key features were projected using their **Compound Annual Growth Rates (CAGR)**, simulating future development trends. The model was trained on the latest available data and applied to each country for year-by-year emission forecasting, helping uncover trends that inform climate strategy.

---

## 🧪 Methodology

1. **Data Collection**  
   Cleaned country-level development data

2. **Data Preprocessing & Feature Selection**  
   Filtered relevant indicators; handled missing values

3. **Exploratory Data Analysis (EDA)**  
   Identified patterns and correlations

4. **CAGR Calculation**  
   Computed growth rates for selected features

5. **Model Training**  
   Trained Random Forest Regressor with CV and tuning

6. **Forecasting**  
   Simulated next 20 years using CAGR-based values

7. **Prediction & Visualization**  
   Predicted CO₂ per capita and visualized trends

---

## 📊 Results

- Trained model achieved strong predictive performance:
  - **R² Score**: ~0.92  
  - **MSE / RMSE**: Evaluated using `sklearn.metrics`
- Visualized upward trends in developing countries and declining trends in developed countries

---



