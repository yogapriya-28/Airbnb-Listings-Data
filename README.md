# 📊 Airbnb Listings Data Analysis Project

## 📌 Project Overview
This project analyzes Airbnb listing data to extract meaningful insights using Exploratory Data Analysis (EDA) and machine learning techniques such as K-Means Clustering, Logistic Regression, and Linear Regression.

The goal is to understand key factors influencing pricing, customer satisfaction, and listing performance.

---

## 📁 Dataset
**File:** `Airbnb_data_Selected_Info.xlsx`

The dataset contains:
- Property characteristics
- Pricing details
- Accommodation capacity
- Reviews and ratings
- Host and listing attributes

---

## 🎯 Project Objectives

### 1. Exploratory Data Analysis (EDA)
- Handle missing values
- Perform descriptive statistics
- Detect outliers
- Conduct business-based checks
- Create visualizations for insights

---

### 2. K-Means Clustering
Variables used:
- Price  
- Accommodates  
- Bathrooms  
- Number of Reviews  
- Bedrooms  
- Beds  

Tasks:
- Determine optimal clusters using Elbow Method
- Segment listings
- Profile clusters
- Generate business insights

---

### 3. Logistic Regression
- Selected cluster: Cluster with maximum observations

#### Target Variable:
**Very High Score**
- 1 → Review Score Rating ≥ 98  
- 0 → Otherwise  

#### Features:
- Price  
- Bathrooms  
- Bedrooms  
- Beds  
- Cleaning Fees  

#### Steps:
- Train-test split (90:10)
- Model building
- Evaluation using:
  - Confusion Matrix
  - Accuracy
  - Precision
  - Recall

---

### 4. Linear Regression
Target Variable:
- Review Score Rating (continuous)

Features:
- Price  
- Bathrooms  
- Bedrooms  
- Beds  
- Cleaning Fees  

Tasks:
- Train-test split (90:10)
- Interpret coefficients
- Analyze statistical significance
- Evaluate model performance
- Compare with Logistic Regression

---

## 🛠️ Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Statsmodels  

---

## 📊 Key Outcomes
- Data cleaning and preprocessing insights
- Visual analysis of listing characteristics
- Cluster-based segmentation
- Predictive modeling results
- Business recommendations

---

## 📈 Business Insights
- Factors influencing high review scores
- Impact of pricing on customer satisfaction
- Characteristics of top-performing listings
- Optimization strategies for Airbnb hosts

---

## 📄 Submission Details
- Final report in PDF format
- Includes:
  - Output screenshots (tables, plots, models)
  - Interpretations and insights
- Python code is not included in the report

---

## 💡 Conclusion
This project demonstrates how data analysis and machine learning can be used to understand Airbnb listings and improve business decision-making through data-driven insights.

---

## 🚀 How to Run
1. Load dataset:
   ```python
   import pandas as pd
   df = pd.read_excel("Airbnb_data_Selected_Info.xlsx")
