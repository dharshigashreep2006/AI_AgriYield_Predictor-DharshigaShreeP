# 🌾 AgriYield Predictor — Forecasting Crop Yield using Environmental and Soil Data

## 📌 Project Aim
To predict agricultural crop yield using environmental and soil data with AI-based regression models.

## 🧹 Preprocessing & EDA
- Handled missing values and duplicates.
- Normalized numerical columns (Rainfall, Fertilizer, Pesticide).
- Encoded categorical features (Crop, Season, State).
- Performed detailed EDA with correlation heatmap, crop yield distribution, and crop frequency plots.

## 🤖 Model Used
- Random Forest Regressor (Best performing model)
- Metrics:
  - **R² Score:** 0.89  
  - **MAE:** 0.12  

## 🚀 Deployment
Deployed on Streamlit
Link: https://smartyield-uwwl4w8xniqeuvn2w889dx.streamlit.app/

## 📂 Dataset
Contains features like:
- Area
- Production
- Annual Rainfall
- Fertilizer
- Pesticide
- Crop
- Season
- State
- Yield (Target)
