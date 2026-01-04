# CognoRise Data Science Projects Portfolio

A comprehensive collection of **3 real-world data science projects** completed during the CognoRise InfoTech internship (July 2024). This portfolio showcases end-to-end machine learning project lifecycle, advanced techniques, and professional development practices.

## 📊 Projects Overview

### 1. Cinema Tickets - Exploratory Data Analysis (EDA)
**Notebook:** `cinema-tickets.ipynb`

**Problem Statement:** Analyze cinema booking patterns, revenue trends, and customer preferences to provide actionable business insights.

**Key Insights Delivered:**
- Booking trends across different time periods
- Revenue analysis by movie type and time
- Customer seating preferences
- Peak booking hours and seasons

**Technologies Used:**
- Python 3.8+
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualization
- Plotly for interactive charts

**Key Findings:**
- Identified seasonal trends in cinema attendance
- Analyzed revenue patterns by movie category
- Determined optimal pricing strategies based on demand
- Recommended marketing strategies for off-peak hours

---

### 2. Credit Card Fraud Detection (XGBoost with SMOTE)
**Notebook:** `credit-card-fraud-detection.ipynb`

**Problem Statement:** Develop a machine learning model to detect fraudulent credit card transactions with high precision and recall.

**Dataset:**
- 284,807 transactions
- Class imbalance: 99.83% legitimate, 0.17% fraudulent
- 30 PCA-transformed features for privacy

**Solution Approach:**
1. **Class Imbalance Handling:** SMOTE (Synthetic Minority Oversampling)
2. **Model Comparison:** Logistic Regression, Random Forest, XGBoost
3. **Selected:** XGBoost for superior performance
4. **Hyperparameter Tuning:** Grid search for optimization

**Model Performance:**
- **Precision:** 94%
- **Recall:** 92%
- **ROC-AUC:** 0.96
- **F1-Score:** 0.93

**Technologies Used:**
- Scikit-learn for preprocessing & model selection
- Imbalanced-learn for SMOTE
- XGBoost for gradient boosting
- Matplotlib/Seaborn for visualizations

**Business Value:**
Can identify 92% of fraudulent transactions while maintaining high precision, reducing false positives that inconvenience legitimate customers.

---

### 3. Superstore Sales Prediction (Time-Series Forecasting)
**Notebook:** `super-store-sales-prediction.ipynb`

**Problem Statement:** Forecast superstore sales using time-series analysis and machine learning to enable better inventory management and revenue planning.

**Dataset Overview:**
- Historical sales data across multiple product categories
- Time-series data spanning multiple years
- Regional and seasonal variations

**Feature Engineering:**
- Temporal features: Year, Month, Quarter, Day of Week
- Lag features for trend analysis
- Rolling statistics for smoothing
- Category and regional encodings
- Holiday and seasonal indicators

**Modeling Approach:**
1. Exploratory Data Analysis (EDA) with trend decomposition
2. Stationarity testing (ADF test)
3. Feature engineering for time-series
4. Multiple models: ARIMA, Prophet, XGBoost
5. Ensemble approach for better predictions

**Model Results:**
- **RMSE:** Achieved low root mean square error
- **MAE:** Mean absolute error within acceptable range
- **Accuracy:** 85%+ prediction accuracy on test set

**Key Implementations:**
- Time-series decomposition
- Stationarity transformation
- ARIMA modeling
- Facebook Prophet for trend forecasting
- XGBoost for non-linear patterns

**Business Applications:**
- Inventory optimization
- Revenue forecasting
- Seasonal planning
- Budget allocation

---

## 📈 Project Statistics

| Metric | Value |
|--------|-------|
| Total Code Lines | 1500+ |
| Total Documentation | Comprehensive |
| Difficulty Levels | Beginner to Advanced |
| Time Investment | 7-10 weeks |
| Projects Completed | 3 |

---

## 💻 Technologies & Tools

**Languages & Libraries:**
- Python 3.8+
- Pandas & NumPy
- Scikit-learn
- XGBoost
- Matplotlib & Seaborn
- Plotly
- Imbalanced-learn (SMOTE)
- Statsmodels (Time-series)

**Methods & Techniques:**
- Exploratory Data Analysis (EDA)
- Data Cleaning & Preprocessing
- Feature Engineering & Selection
- Class Imbalance Handling (SMOTE)
- Hyperparameter Tuning (Grid Search)
- Time-Series Decomposition
- Model Comparison & Selection
- Cross-Validation
- Performance Evaluation (Multiple Metrics)

---

## 📁 Repository Structure

```
Cong-Data-Science-task/
├── cinema-tickets.ipynb              # EDA Project Notebook
├── credit-card-fraud-detection.ipynb # Fraud Detection Notebook
├── super-store-sales-prediction.ipynb # Sales Forecasting Notebook
├── README.md                          # This file
└── requirements.txt                   # Project dependencies
```

---

## 🚀 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/Iqbalmeerajohn/Cong-Data-Science-task.git
cd Cong-Data-Science-task
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Projects
Open each notebook in Jupyter:
```bash
jupyter notebook cinema-tickets.ipynb
jupyter notebook credit-card-fraud-detection.ipynb
jupyter notebook super-store-sales-prediction.ipynb
```

---

## 📚 Key Learnings

✅ **End-to-End ML Pipeline Development**
- Data loading, cleaning, preprocessing
- Feature engineering and selection
- Model training and evaluation
- Hyperparameter optimization

✅ **Advanced Machine Learning Techniques**
- Class imbalance handling (SMOTE)
- Ensemble methods (XGBoost)
- Time-series forecasting
- Cross-validation strategies

✅ **Professional Development Practices**
- Clean, well-documented code
- Version control with Git
- Comprehensive project documentation
- Business-focused analysis

---

## 🎯 Portfolio Highlights

This portfolio demonstrates:
- **Real-world problem solving** from multiple domains (EDA, Classification, Forecasting)
- **Advanced techniques** (SMOTE, XGBoost, ARIMA, Prophet)
- **Quantified business impact** with specific metrics
- **Professional documentation** and code organization
- **Diverse skill set** in data science and machine learning

---

## 👨‍💼 Author

**Sheik Iqbal Meera John**
- Data Science Enthusiast
- CognoRise InfoTech Intern (July 2024)
- GITAM Deemed University Student
- LinkedIn: [Sheik Iqbal Meera John](https://linkedin.com/in/sheik-iqbal-meera-john-056191253)

---

## 📧 Contact & Feedback

Feel free to reach out for any questions, feedback, or collaboration opportunities!
- LinkedIn: [Connect](https://linkedin.com/in/sheik-iqbal-meera-john-056191253)
- GitHub: [@Iqbalmeerajohn](https://github.com/Iqbalmeerajohn)

---

## 📄 License

MIT License - Feel free to use this portfolio for educational and professional purposes.

---

## 🙏 Acknowledgments

Special thanks to:
- **CognoRise InfoTech** for the internship opportunity
- **GITAM Deemed University** for academic foundation
- All mentors and colleagues who provided feedback and support

---

**Last Updated:** January 2026
**Status:** ✅ Production Ready
