# Data Analytics and Intelligence

## Overview  
This project was completed as part of the **I304 – Data Analytics and Intelligence** course.  
It applies **data analytics and machine learning techniques** using Python to solve real-world business intelligence problems.  

The assignment consists of four major tasks:  
1. **Linear Regression** – Stock price prediction using Yahoo Finance API  
2. **Data Clustering** – Credit card dataset clustering using K-Means  
3. **Data Classification** – Breast Cancer Wisconsin dataset classification  
4. **Principal Component Analysis (PCA)** – Dimensionality reduction with classification  

---

## Technologies Used
- **Python 3.x**  
- **Pandas, NumPy** – Data manipulation  
- **Matplotlib, Seaborn** – Data visualization  
- **scikit-learn** – Machine learning (Regression, Classification, Clustering, PCA)  
- **yfinance** – Stock market data retrieval  

---

## Tasks Breakdown

### Task 1: Linear Regression – Stock Price Prediction
- Retrieved stock data using **Yahoo Finance API**  
- Performed **exploratory data analysis** on stock features  
- Built a **multivariate linear regression model** to predict stock closing prices  
- Evaluated model performance with **R² score**  
- Tested predictions on custom input values  

### Task 2: Data Clustering – Credit Card Dataset
- Applied **K-Means clustering** (clusters = 3 → 15)  
- Visualized results with different color-coded clusters  
- Determined the most suitable number of clusters  

### Task 3: Data Classification – Breast Cancer Dataset
- Preprocessed and scaled the dataset  
- Trained two classifiers:  
  - **Logistic Regression**  
  - **K-Nearest Neighbours (KNN)**  
- Compared accuracy results between models  

### Task 4: Principal Component Analysis (PCA)
- Performed **PCA with n_components=2** on Wine dataset  
- Reduced dimensionality while preserving key variance  
- Trained a **Logistic Regression classifier** on reduced data  
- Visualized results with a scatter plot  

---

## How to Run
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/data-analytics-assessment1.git
   cd data-analytics-assessment1
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run any task script, e.g.:  
   ```bash
   python Task1_LinearRegression/linear_regression_stock.py
   ```

---

## Results Summary
- **Regression**: Achieved meaningful stock price predictions with acceptable R² scores.  
- **Clustering**: K-Means formed well-separated customer groups in the credit card dataset.  
- **Classification**: Both Logistic Regression and KNN achieved strong accuracy; Logistic Regression performed slightly better.  
- **PCA**: Successfully reduced data to 2D while maintaining classification effectiveness.  
