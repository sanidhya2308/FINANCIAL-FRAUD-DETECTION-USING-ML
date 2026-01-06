# FINANCIAL-FRAUD-DETECTION-USING-ML
🚀 Built a Credit Card Fraud Detection System using ML + Tableau. 🔍 Performed EDA, anomaly detection, and trained models (RF, XGBoost, Logistic Regression) with high fraud recall. 📊 Created location-wise &amp; yearly dashboards to spot high-risk zones and trends. 🛡 Turning data into real-world fraud prevention.
https://colab.research.google.com/drive/1_PSk0BU_4xZMp5XpDub3GAuyxRWoay8j#scrollTo=mWlRP0aiiMzQ
🚀 LinkedIn Post: Credit Card Fraud Detection — Full Project + Visual Insights
🔍 Credit card fraud is one of the fastest-growing financial crimes worldwide, and businesses are under increasing pressure to safeguard customer transactions in real time.
 To address this challenge, I recently built a Fraud Detection System using machine learning and visual analytics — combining data preprocessing, EDA, anomaly analysis, model building, and insights visualization.
Here’s a breakdown of the project 👇
📌 🔧 Project Overview
The goal was to predict fraudulent credit card transactions using machine learning models and highlight location-wise patterns, high-risk zones, and yearly trends through dashboards.
Tech Stack
✔ Python
 ✔ Pandas, NumPy
 ✔ Matplotlib / Seaborn
 ✔ Scikit-learn
 ✔ Tableau for visualization
 ✔ Machine Learning Models (Random Forest, XGBoost, Logistic Regression)
📊 📍 Location-Based Fraud Analysis
A detailed Tableau dashboard was created to uncover:
1️⃣ Fraud Amount by City
The first visualization compares total transaction amounts across cities such as:
 San Jose, Philadelphia, Los Angeles, New York, Phoenix, San Antonio, Houston, Dallas, San Diego, Chicago
This helps in identifying high-volume locations that require stricter monitoring.
📆 2️⃣ Yearly Comparison (2023 vs 2024)
The second chart breaks down each location into two bars:
Total Transaction Amount
Fraud Amount
This reveals patterns such as:
🔵 Some cities showing significant fraud growth from 2023 → 2024
 🟠 Consistent fraud patterns in medium-risk locations
 🔴 Sudden spikes signaling emerging fraud hotspots
Such comparison helps financial institutions prioritize investigation and resource allocation.
🤖 3️⃣ Machine Learning Component
The ML pipeline included:
✔ Exploratory Data Analysis (EDA)
Trend identification
Correlation heatmaps
Outlier detection
Transaction type segmentation
✔ Model Building
Models were trained to classify transactions as fraud / non-fraud using features such as:
Transaction amount
Historical balance
Origin & destination accounts
Transaction type
Location
✔ Evaluation
Precision/Recall (critical because fraud detection requires high recall)
ROC-AUC
Confusion Matrix
The final ensemble model achieved high accuracy and robust fraud recall, minimizing false negatives.
🛡 Why This Matters
Fraud detection is not just a data science challenge —
 it is a security problem, a financial problem, and a customer-trust problem.
This project helps demonstrate:
 ✔ Efficient ML pipeline design
 ✔ Actionable insights through dashboards
 ✔ Real-world application of anomaly detection 
