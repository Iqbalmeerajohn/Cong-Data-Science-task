# 💼 Data Science Project Portfolio
### Machine Learning | Predictive Analytics | Business Intelligence

![Python](https://img.shields.io/badge/Python-3.8+-3776AB?style=flat&logo=python&logoColor=white)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.3-F7931E?style=flat&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-2.0-FA5202?style=flat)
![Pandas](https://img.shields.io/badge/Pandas-2.0-150458?style=flat&logo=pandas)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37726?style=flat&logo=jupyter)

> End-to-end machine learning and analytics projects built during the **CognoRise InfoTech Data Science Internship (July 2024)**. Each project covers the full pipeline: data ingestion → EDA → preprocessing → modelling → evaluation.

---

## 📂 Projects in This Repository

| # | Project | Technique | Key Result |
|---|---------|-----------|------------|
| 1 | [Retail Sales Prediction](#1-retail-sales-prediction-system) | Time-Series Forecasting | 85%+ accuracy |
| 2 | [Credit Card Fraud Detection](#2-credit-card-fraud-detection) | Classification + SMOTE | 0.96 ROC-AUC |
| 3 | [Cinema Tickets EDA](#3-cinema-tickets-eda) | Exploratory Data Analysis | 10K+ bookings analyzed |

---

## 1. 📊 Retail Sales Prediction System

> *Forecasting future retail revenue to support inventory planning and business decision-making.*

**Problem:** Retail businesses struggle to optimize stock and staffing without reliable demand forecasts.

**Solution:** Built an ensemble time-series forecasting pipeline using ARIMA and XGBoost on historical superstore sales data.

### Highlights
- Performed comprehensive **EDA** to uncover seasonal trends, regional patterns, and product category performance
- Engineered time-based features (lag variables, rolling averages, seasonality indicators)
- Benchmarked ARIMA, Prophet, and XGBoost — XGBoost ensemble achieved **85%+ prediction accuracy**
- Generated business insights on top-performing categories and regions

### Tech Stack
`Python` `Pandas` `NumPy` `Scikit-learn` `XGBoost` `Statsmodels` `Facebook Prophet` `Matplotlib` `Seaborn`

**Notebook:** [`super-store-sales-prediction.ipynb`](./super-store-sales-prediction.ipynb)

---

## 2. 🔐 Credit Card Fraud Detection

> *Building a robust fraud classifier that catches 92% of fraudulent transactions without flooding legitimate users with false alerts.*

**Problem:** Credit card fraud datasets are highly imbalanced (fraud < 1% of transactions), making standard classifiers ineffective.

**Solution:** Applied **SMOTE** (Synthetic Minority Oversampling Technique) to handle class imbalance and trained an XGBoost classifier with hyperparameter tuning.

### Highlights
- Handled severe class imbalance using **SMOTE oversampling**
- Achieved **94% Precision | 92% Recall | 0.96 ROC-AUC**
- Optimized decision threshold for business-appropriate false positive rates
- Visualized feature importance to identify top fraud indicators

### Tech Stack
`Python` `Scikit-learn` `XGBoost` `Imbalanced-learn` `Pandas` `Matplotlib` `Seaborn`

**Notebook:** [`credit-card-fraud-detection.ipynb`](./credit-card-fraud-detection.ipynb)

---

## 3. 🎬 Cinema Tickets EDA

> *Uncovering booking patterns, revenue drivers, and audience behaviour from 10,000+ cinema transactions.*

**Problem:** Cinema operators lack visibility into which shows, time slots, and ticket types drive the most revenue.

**Solution:** Conducted deep **Exploratory Data Analysis** on a cinema ticketing dataset to surface actionable business intelligence.

### Highlights
- Analyzed **10,000+ booking records** across movie types, time slots, and pricing tiers
- Identified peak booking windows and highest-revenue show categories
- Built visualizations for booking heatmaps, revenue by genre, and pricing sensitivity
- Delivered recommendations for dynamic pricing and inventory allocation

### Tech Stack
`Python` `Pandas` `NumPy` `Matplotlib` `Seaborn` `Plotly`

**Notebook:** [`cinema-tickets.ipynb`](./cinema-tickets.ipynb)

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/Iqbalmeerajohn/Cong-Data-Science-task.git
cd Cong-Data-Science-task

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter
jupyter notebook
```

---

## 🛠️ Full Tech Stack

| Category | Tools |
|----------|-------|
| **Languages** | Python 3.8+ |
| **ML Libraries** | Scikit-learn, XGBoost, Imbalanced-learn |
| **Time Series** | Statsmodels (ARIMA), Facebook Prophet |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Environment** | Jupyter Notebook |

---

## 👨‍💻 Author

**Sheik Iqbal Meera John**  
B.Tech CSE (Data Science) — GITAM University, 2026  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/sheik-iqbal-meera-john-056191253)  
[![GitHub](https://img.shields.io/badge/GitHub-Iqbalmeerajohn-181717?style=flat&logo=github)](https://github.com/Iqbalmeerajohn)
