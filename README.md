# AetherForge – Predictive Asset Failure Intelligence System

## Project Overview

AetherForge is an end-to-end **Predictive Asset Failure Intelligence System** designed to estimate the Remaining Useful Life (RUL) of turbofan engines using multivariate sensor data and deep learning.

Unlike traditional predictive maintenance systems that only provide numerical risk scores, AetherForge connects sensor-based predictions with technical knowledge to generate more useful maintenance insights.

**Core Flow:**  
Sensor Data → Deep Learning Prediction → Knowledge Retrieval → Actionable Recommendations

## Dataset

- **NASA CMAPSS FD001** (Turbofan Engine Degradation Simulation)
- 100 training engines + 100 test engines
- Multivariate time-series data including vibration, temperature, pressure, and other sensor readings

## Technologies Used

- **Python**
- **Pandas & NumPy** – Data processing
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Preprocessing and evaluation
- **TensorFlow / Keras (LSTM)** – Deep Learning model for RUL prediction
- **TF-IDF** – Document retrieval for maintenance knowledge

## Project Workflow

1. Exploratory Data Analysis of sensor data
2. Data cleaning and removal of constant sensors
3. Feature selection and normalization
4. Sequence creation for time-series modeling
5. LSTM model training for RUL prediction
6. Model evaluation using MAE and RMSE
7. Document retrieval using TF-IDF
8. Generation of intelligence reports with risk level and recommended actions

## Model Performance (FD001 Test Set)

| Metric | Value  |
|--------|--------|
| MAE    | 16.67  |
| RMSE   | 24.45  |

## Project Objectives

- Estimate Remaining Useful Life of industrial assets
- Analyze sensor patterns associated with equipment degradation
- Build a deep learning model for time-series RUL prediction
- Connect predictions with technical knowledge for better decision support
- Demonstrate an end-to-end predictive maintenance pipeline

## Repository Contents

- `AetherForge.ipynb` — Complete project implementation (EDA to End-to-End pipeline)
- `README.md` — Project documentation
- `models/` — Saved LSTM model and scaler (optional)

## How to Run

1. Clone this repository
2. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow joblib

##  Author

**Ritisha Atone**

Aspiring Data Scientist | Python | SQL | Machine Learning | Power BI
