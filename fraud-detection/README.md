# Credit Card Fraud Detection

## Project Overview
A comprehensive machine learning project for detecting fraudulent credit card transactions using advanced classification algorithms and data analysis techniques.

## Objective
Build and deploy a fraud detection model that can:
- Identify fraudulent transactions with high accuracy and precision
- Minimize false positives to avoid blocking legitimate transactions
- Provide interpretable predictions for fraud prevention strategies

## Dataset Information
- **Source**: Credit card transaction dataset
- **Size**: Large-scale imbalanced dataset with fraud and legitimate transactions
- **Features**: Transaction amount, time, merchant details, customer information
- **Target**: Binary classification (Fraudulent vs. Legitimate)

## Key Analysis Components

### 1. Data Exploration
- Dataset structure and statistical analysis
- Class distribution analysis (fraud vs. legitimate)
- Transaction patterns and anomalies
- Time-series analysis of fraud patterns

### 2. Data Preprocessing
- Handling missing values
- Feature scaling and normalization
- Dealing with class imbalance
- Feature engineering from raw transaction data

### 3. Exploratory Data Analysis (EDA)
- Fraud distribution across transaction amounts
- Temporal patterns of fraudulent activities
- Correlation analysis between features
- Statistical comparisons between fraud and legitimate transactions

### 4. Feature Engineering
- Creation of aggregate features
- Time-based features (hour, day, week patterns)
- Risk indicators and behavioral patterns

### 5. Model Development
- Multiple classification algorithms tested:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - Neural Networks
- Hyperparameter tuning and optimization
- Model evaluation and comparison

### 6. Model Evaluation
- Accuracy, Precision, Recall metrics
- F1-Score and ROC-AUC analysis
- Confusion Matrix interpretation
- Threshold optimization for business requirements

## Key Findings
- Identified critical features for fraud prediction
- Established optimal classification threshold
- Achieved high recall for fraud detection
- Demonstrated model robustness on test data

## Technologies Used
- **Python**: Core programming language
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Scikit-learn**: Machine learning algorithms
- **Matplotlib & Seaborn**: Data visualization
- **XGBoost**: Gradient boosting implementation

## Results Summary
- Model achieved strong performance on validation data
- Successfully balanced precision and recall metrics
- Scalable solution for production implementation

## Usage Instructions
1. Load and explore the dataset
2. Run data preprocessing pipeline
3. Execute exploratory analysis
4. Train and evaluate models
5. Make predictions on new transactions

## Related Projects
- Cinema Tickets EDA
- Super Store Sales Prediction

## Author
Iqbal Meeraj John

## Notes
For detailed analysis, code implementation, and visualizations, see the Jupyter notebook in this folder.
