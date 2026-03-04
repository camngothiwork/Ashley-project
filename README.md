# Ashley-project
## 📊 Demand Forecasting for Ashley’s Outdoor & Accessories Product Line  
**MIS 495 – Strategic Business Analytics | March 2025**
---
### 📌 Project Overview
This project forecasts Q1 2025 demand for Ashley’s Outdoor and Accessories product lines using three years of historical sales data.  
The objective is to improve forecasting accuracy beyond traditional methods (e.g., Moving Average) by applying statistical and machine learning models to support inventory optimization and supply chain decision-making.
### 🔎 Scope
- 10 warehouses  
- 205 Outdoor series (613 SKUs)  
- 1,539 Accessories series (1,578 SKUs)  
- Only records with production in 2024 were considered eligible for modeling  
### ⚙️ Methodology
- Data cleaning & preprocessing  
- Exploratory analysis (seasonality & volatility detection)  
- Model training & validation  
- Model evaluation using wMAPE  
- Deployment via Gradio web interface  
### 🤖 Models Applied
- ARIMA  
- Holt-Winters  
- XGBoost  
- Neural Network  
- LSTM  
- Ensemble models  
Models were selected based on demand patterns (stable, mildly fluctuating, highly volatile).
### 📈 Key Results
- Successfully built forecasting models for **36% of Outdoor series** and **14% of Accessories series**  
- Achieved target error thresholds on **73 Outdoor series** and **216 Accessories series**  
- Improved underperforming series using LSTM (reduced wMAPE from **98% to 17.25%**)  
- Provided recommendations to enhance inventory planning and operational efficiency  
### 🚀 Future Improvements
- Expand deep learning integration with stronger computational resources  
- Develop a more robust ensemble framework  
- Improve forecasting performance for highly volatile product series  
