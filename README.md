# -Credit-Card-Fraud-Detection---Exploratory-Data-Analysis-EDA-
This project presents a comprehensive exploratory data analysis (EDA) on a credit card transaction dataset to understand the patterns and challenges involved in detecting fraudulent activities. The dataset contains 11,959 transactions with 30 anonymized features (V1–V28), a timestamp (`Time`), transaction `Amount`, and a `Class` label indicating fraud (1) or legitimate (0) transactions.

 Objectives:
- Understand the distribution and imbalance in the dataset.
- Explore feature relationships, trends, and anomalies.
- Visualize patterns that differentiate fraudulent transactions from legitimate ones.
- Identify useful insights that could guide model building and fraud detection.

---

Key Insights & Analysis:

- Class Imbalance:  
  The dataset is highly imbalanced with a very small percentage of transactions marked as fraudulent.

- Amount Analysis:  
  Fraudulent transactions tend to occur at various amounts, but visualizations help show how certain ranges are more suspicious.

- Time-based Trends:
  Analysis of transaction times reveals whether fraudulent activities are more likely at specific times of day.

- Feature Distributions (V1–V28):  
  Violin plots and box plots were used to observe how these anonymized features differ between fraud and normal transactions.

- Correlation Heatmaps:  
  Help identify any strong relationships among features and potential multicollinearity issues.

- Dimensionality Reduction:  
  PCA was used to reduce high-dimensional features for better visualization and interpretation.

---

Technologies Used:
- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook
- Git & GitHub

---

Dataset Info:
- Rows: 11,959  
- Columns: 31  
- Features: Time, V1–V28 (PCA components), Amount, Class  
- Label: `Class` → 0 = Legitimate, 1 = Fraud

---
License & Acknowledgments:
Dataset sourced from a [Kaggle competition / open dataset].  
This analysis was done for educational and research purposes.
