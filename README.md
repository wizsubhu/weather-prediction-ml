# 🌦️ Weather Prediction Using Machine Learning & Time Series Analysis

This project predicts future weather conditions using supervised learning and time series modeling. It includes data cleaning, exploratory analysis, feature engineering, model training with Random Forest and XGBoost, and performance evaluation using regression metrics. Ideal for real-world climate forecasting applications.

---

## 🚀 Project Highlights

- 🌐 Real-world weather dataset with temperature, humidity, and pressure
- 🧹 Data Preprocessing, Feature Engineering & Time-based Features
- 📊 Exploratory Analysis: Trends, heatmaps, seasonal insights
- 🤖 Models Used: Random Forest Regressor, XGBoost, Linear Regression
- 📈 Evaluation: RMSE, MAE, R², Residual Analysis

---

## 📂 Dataset

- **Source**: Public historical weather data (e.g., Kaggle or NOAA)
- **Target Variables**: Temperature or Humidity
- **Features**: Time, pressure, wind speed, humidity, temperature, etc.

---

## 🛠️ Tools & Technologies

| Category         | Tools / Libraries                              |
|------------------|--------------------------------------------------|
| Language         | Python                                           |
| Data Wrangling   | Pandas, NumPy                                    |
| Visualization    | Matplotlib, Seaborn, Plotly                      |
| Modeling         | Scikit-learn, XGBoost, RandomForestRegressor     |
| Evaluation       | RMSE, MAE, R² Score, Cross-Validation            |
| Time Series      | Lag Features, Rolling Averages                   |

---

## 📊 Exploratory Data Analysis

- 📈 Time Series Plots: Daily and monthly trends
- 🌡️ Correlation heatmaps
- 📉 Rolling averages for smoothing
- 🔍 Seasonal variation and trend decomposition

---

## ⚙️ ML Workflow

### 1. Data Preprocessing
- Parse date/time
- Handle missing values and outliers
- Generate lag and rolling window features

### 2. Model Training
- **Random Forest Regressor**
- **XGBoost Regressor**
- **Linear Regression (as baseline)**

### 3. Evaluation
- Regression metrics: **RMSE**, **MAE**, and **R²**
- Prediction vs actual comparison
- Residual distribution plots

---

## 📦 How to Run the Project

```bash
# Clone the repo
git clone https://github.com/yourusername/weather-forecast-ml.git
cd weather-forecast-ml

# Install dependencies
pip install -r requirements.txt

# Run the notebook
jupyter notebook "project 2 code.ipynb"

