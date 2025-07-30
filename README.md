# 🚚 Food Delivery Time Prediction – Mini Project

This mini-project analyzes a food delivery dataset to explore what factors affect delivery time. The project includes exploratory data analysis (EDA), data visualization, feature engineering (like GPS-based distance calculation), and preparation for machine learning.

---

## 📦 Dataset Overview

The dataset includes delivery information such as:

- Delivery person ID, age, and ratings
- Restaurant and delivery location (latitude/longitude)
- Type of order and vehicle used
- Time taken for delivery (in minutes)

---

## 🎯 Objectives

- Understand patterns in delivery time
- Analyze impact of order type, vehicle type, and ratings
- Calculate delivery distance using coordinates (Haversine formula)
- Engineer new features like `Delivery_distance_km`, `Speed_kmph`, and age groups
- Prepare clean dataset for future ML modeling

---

## 📊 Key Exploratory Steps

- Countplot, histogram, KDE plot, and boxplots for visual understanding
- Group-wise analysis (e.g., average time by vehicle or order type)
- Correlation heatmap between numeric features

---

## 🧮 Feature Engineering

- `Delivery_distance_km` using Haversine formula
- `Speed_kmph` = distance / time
- `Age_Group` categorization
- Encoding for ML-readiness

---

## ✅ Key Insights

- Motorcycle is the most frequently used vehicle
- Buffet orders take the most time on average
- Delivery distance significantly affects time
- Ratings show weak correlation with delivery time

---

## 💡 Next Steps (Optional for Expansion)

- Build a regression model to predict delivery time
- Classify fast vs. slow deliveries using ML
- Tune features using scikit-learn pipelines

---

## 🛠 Technologies Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Jupyter Notebook

---

## 📁 Files

- `Food_Delivery_Time_Prediction_Case_Study.ipynb` – Main notebook
- `README.md` – Project overview and instructions
