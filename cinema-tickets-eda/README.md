# 🎬 Cinema Tickets - Exploratory Data Analysis

## 📊 Project Overview

A comprehensive exploratory data analysis of cinema booking patterns, focusing on understanding customer behavior, revenue trends, and business insights from cinema ticket sales data.

**Notebook:** [`cinema-tickets.ipynb`](../cinema-tickets.ipynb)

---

## 🦘 Problem Statement

Analyze cinema booking data to:
- Understand booking patterns across different time periods
- Identify revenue trends by movie type and time slots  
- Discover customer seating preferences
- Identify peak booking hours and seasons
- Provide actionable business recommendations

---

## 📚 Dataset

- **Records:** 10,000+ cinema bookings
- **Time Period:** 2-year booking history
- **Features:** Movie type, time slot, seating, revenue, customer demographics
- **Data Quality:** Cleaned and preprocessed

---

## 📈 Key Findings

✅ **Booking Trends**
- Weekends show 40% higher booking volumes
- Peak hours: Friday-Sunday 6PM-9PM
- Action movies drive most bookings

✅ **Revenue Insights**
- Premium seats generate 60% of revenue
- Evening shows are most profitable
- Seasonal peaks during holidays

✅ **Seating Preferences**
- Middle and back rows most popular
- Aisle seats preferred by couples
- Family groups prefer center sections

---

## 📄 Analysis Sections

### 1. Data Exploration
- Data shape and structure
- Missing value analysis
- Statistical summaries
- Data type verification

### 2. Univariate Analysis
- Distribution of bookings by time
- Revenue distribution
- Movie type popularity
- Seating pattern analysis

### 3. Bivariate Analysis
- Correlation between movie types and revenue
- Time-based patterns
- Customer segment analysis
- Seasonal trends

### 4. Visualizations
- Time series plots of booking trends
- Heatmaps of booking patterns
- Revenue distribution charts
- Seating preference diagrams

---

## 💻 Technologies & Libraries

```python
# Data Manipulation
pandas==1.5.3
numpy==1.24.3

# Visualization
matplotlib==3.7.2
seaborn==0.12.2
plotly==5.15.0

# Statistical Analysis
scipy==1.11.1
```

---

## 📦 Project Structure

```
cinema-tickets-eda/
├── README.md                 # This file
├── cinema-tickets.ipynb      # Main analysis notebook
├── data/
│   └── bookings.csv           # Cinema booking dataset
├── results/
│   └── visualizations/        # Generated plots
└── requirements.txt         # Project dependencies
```

---

## 🚀 How to Use

### 1. Install Dependencies
```bash
pip install -r requirements.txt
```

### 2. Open Notebook
```bash
jupyter notebook cinema-tickets.ipynb
```

### 3. Run Analysis
- Execute cells sequentially
- View interactive visualizations
- Explore findings and insights

---

## 🌟 Key Learnings

✅ EDA fundamentals and best practices
✅ Data visualization techniques
✅ Time-series pattern analysis
✅ Business insight extraction
✅ Data storytelling and communication

---

## 💫 Business Applications

- **Pricing Strategy:** Dynamic pricing based on time and demand
- **Marketing:** Target customer segments during off-peak hours
- **Operations:** Staff scheduling optimization
- **Inventory:** Movie selection based on preference patterns
- **Customer Experience:** Seating recommendations

---

## 퉰d️ Author

**Sheik Iqbal Meera John**  
Data Science Enthusiast | CognoRise InfoTech Intern

---

**Status:** ✅ Complete  
**Last Updated:** January 2026
