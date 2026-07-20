# 🚦 Accident Hotspot Prediction System using Machine Learning and Power BI

## 📌 Project Overview

Road accidents continue to be one of the leading causes of injuries and fatalities worldwide. Analyzing accident data helps identify high-risk locations, understand the factors contributing to accidents, and support better road safety planning.

This project analyzes a road accident dataset containing **20,000 accident records** with **24 features** collected between **2022 and 2025**. The dataset was cleaned, explored, and transformed using Python before training a **Random Forest Classifier** to predict accident severity. The analytical findings and machine learning results were then presented through an interactive **five-page Power BI dashboard**, enabling users to explore accident trends, identify hotspots, and understand key risk factors.

The project demonstrates an end-to-end data analytics workflow, covering data preprocessing, exploratory data analysis, feature engineering, machine learning, geospatial visualization, and business intelligence.

---

# 🎯 Problem Statement

Road accidents are influenced by multiple factors such as weather conditions, visibility, traffic density, road type, location, and time of day. While large volumes of accident data are available, extracting meaningful insights and identifying accident-prone areas remains challenging without proper analysis.

This project aims to transform raw accident data into actionable insights, identify accident hotspots, analyze the major contributing factors, and develop a machine learning model capable of predicting accident severity. The final results are presented through an interactive Power BI dashboard to support data-driven decision-making.

---

# 🎯 Project Objectives

- Clean and preprocess raw accident data.
- Perform exploratory data analysis (EDA).
- Identify accident hotspots using geospatial analysis.
- Engineer meaningful features for machine learning.
- Build a Random Forest classifier to predict accident severity.
- Evaluate model performance using standard classification metrics.
- Develop an interactive Power BI dashboard.
- Generate business insights and recommendations for road safety.

---

# 📂 Dataset Information

| Attribute | Details |
|-----------|---------|
| Dataset Size | 20,000 Records |
| Features | 24 Columns |
| Time Period | 2022 – 2025 |
| Target Variable | Accident Severity |
| Classes | Minor, Major, Fatal |

### Key Features

- Date
- Time
- Hour
- State
- City
- Latitude
- Longitude
- Weather
- Visibility
- Road Type
- Traffic Density
- Casualties
- Vehicles Involved
- Risk Score
- Accident Severity

---

# 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Data Visualization | Matplotlib, Seaborn, Folium |
| Machine Learning | Scikit-learn |
| Dashboard | Power BI |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |

---

# 🔄 Project Workflow

```
Raw Dataset
      │
      ▼
Data Cleaning & Preprocessing
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Geospatial Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Random Forest Model
      │
      ▼
Model Evaluation
      │
      ▼
Power BI Dashboard
      │
      ▼
Business Insights
```

---

# 📊 Exploratory Data Analysis

The following analyses were performed during EDA:

- Accident Severity Distribution
- Hour-wise Accident Analysis
- Day-wise Accident Analysis
- Weather Condition Analysis
- Road Type Analysis
- Traffic Density Analysis
- Vehicle Type Analysis
- Visibility Analysis
- State-wise Analysis
- City-wise Analysis
- Risk Score Analysis
- Geospatial Hotspot Visualization

---

# 🗺️ Geospatial Analysis

Geospatial visualization was performed using **Folium** to identify accident hotspots across India.

The analysis included:

- Accident Location Map
- Severity-based Accident Map
- Hotspot Identification
- Geographic Risk Visualization

---

# 🤖 Machine Learning

## Model Used

**Random Forest Classifier**

### Why Random Forest?

- Handles structured data effectively
- Reduces overfitting through ensemble learning
- Provides Feature Importance
- Suitable for multi-class classification

---

# 📈 Model Performance

| Metric | Value |
|---------|-------|
| Accuracy | 67.6% |
| Precision | 0.68 |
| Recall | 0.68 |
| F1-Score | 0.67 |

Model evaluation was performed using:

- Confusion Matrix
- Classification Report
- Feature Importance Analysis

---

# 📊 Power BI Dashboard

An interactive dashboard was developed with five analytical pages.

## Dashboard Pages

### 1. Executive Overview

- Total Accidents
- Total Casualties
- Average Risk Score
- Severity Distribution
- State-wise Analysis
- Executive Insights

### 2. Time Analysis

- Hour-wise Trend
- Day-wise Analysis
- Monthly Trend
- Weekend vs Weekday Comparison

### 3. Location Analysis

- State-wise Accidents
- City-wise Distribution
- Geographic Hotspots

### 4. Risk Factor Analysis

- Weather Impact
- Visibility Analysis
- Road Type Analysis
- Traffic Density Analysis
- Risk Score Distribution

### 5. Machine Learning Insights

- Model Accuracy
- Feature Importance
- Confusion Matrix
- Classification Report
- Model Summary

---

# 📌 Key Findings

- Maharashtra recorded the highest number of accidents in the dataset.
- Accident frequency peaked during **2 PM**, indicating increased daytime traffic risk.
- Minor accidents accounted for the largest proportion of reported cases.
- Low visibility and high traffic density were significant contributors to accident severity.
- Random Forest achieved an overall prediction accuracy of **67.6%**.

---

# 💡 Business Recommendations

- Increase traffic monitoring in accident-prone regions.
- Improve road lighting and visibility in high-risk areas.
- Strengthen traffic management during peak traffic hours.
- Deploy predictive analytics to identify potential accident hotspots.
- Support road safety planning using data-driven insights.

---

# 📁 Project Structure

```
Accident-Hotspot-Prediction-System
│
├── data
│   ├── raw
│   └── processed
│
├── notebooks
│   ├── 01_Data_Cleaning.ipynb
│   ├── 02_EDA.ipynb
│   ├── 03_Geospatial_Analysis.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   └── 05_Model_Training_and_Evaluation.ipynb
│
├── dashboard
│   ├── Accident_Hotspot_Dashboard.pbix
│   ├── feature_importance.csv
│   ├── classification_report.csv
│   └── confusion_matrix.png
│
├── models
│
├── images
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 🚀 Future Improvements

- Improve model performance using advanced ensemble techniques.
- Integrate real-time accident and weather APIs.
- Develop a web-based dashboard for live monitoring.
- Build accident risk prediction using deep learning models.
- Deploy the solution as a cloud-based application.

---

# 👨‍💻 Author

**Sameer Saifi**

- **LinkedIn:** *(Add your LinkedIn URL)*
- **GitHub:** *(Add your GitHub Repository URL)*
- **Portfolio:** *(Add your Portfolio URL)*

---

# ⭐ If you found this project useful, consider giving it a star on GitHub.
