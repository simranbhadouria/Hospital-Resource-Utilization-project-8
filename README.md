# Hospital-Resource-Utilization-project-8

## Project Overview

This project focuses on analyzing hospital resource utilization using healthcare operational data. The goal is to identify patterns in patient admissions, bed occupancy, staff allocation, and patient satisfaction to improve hospital efficiency and resource planning.

The project applies Data Analytics, Exploratory Data Analysis (EDA), Machine Learning, Clustering, and Anomaly Detection techniques to generate actionable business insights for healthcare management.

---

## Project Objectives

* Analyze patient admission trends across hospital departments.
* Monitor bed occupancy and resource utilization.
* Evaluate staff allocation efficiency.
* Study patient satisfaction patterns.
* Detect anomalies and unusual workload periods.
* Segment utilization patterns using clustering techniques.
* Predict hospital occupancy levels using Machine Learning.
* Support data-driven decision-making in healthcare operations.

---

## Dataset Information

## Dataset Source

* Kaggle Healthcare Dataset
* Hospital Resource Utilization Dataset

## Dataset Features

| Feature           | Description                        |
| ----------------- | ---------------------------------- |
| week              | Weekly observation period          |
| service           | Hospital department                |
| patients_admitted | Number of admitted patients        |
| avg_stay          | Average patient length of stay     |
| avg_satisfaction  | Average patient satisfaction score |
| max_occupancy     | Maximum bed occupancy              |
| staff_count       | Available staff count              |
| recommended_staff | Recommended staffing level         |

## Departments Included

* ICU
* Emergency
* Surgery
* General Medicine

---

## Tools & Technologies Used

## Programming Language

* Python

## Libraries

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Machine Learning Algorithms

* Random Forest Regressor
* K-Means Clustering
* Principal Component Analysis (PCA)
* Isolation Forest

## Visualization Tools

* Matplotlib
* Seaborn

---

## Project Workflow

1. Data Collection
2. Data Cleaning
3. Data Preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature Engineering
6. Outlier Detection
7. Anomaly Detection
8. PCA Analysis
9. K-Means Clustering
10. Machine Learning Modeling
11. Dashboard Development
12. Business Insights Generation

---

## Exploratory Data Analysis

The following EDA techniques were performed:

## Distribution Analysis

* Histograms
* KDE Plots
* Boxplots

## Correlation Analysis

* Correlation Matrix
* Heatmaps

## Time Series Analysis

* Weekly Admission Trends
* Occupancy Trends

## Comparative Analysis

* Department-wise Admissions
* Satisfaction Analysis
* Resource Utilization Analysis

---

## Outlier & Anomaly Detection

## IQR Method

Used to identify:

* Extreme patient admission periods
* Unusual occupancy levels

## Isolation Forest

Used to detect:

* Resource overload situations
* Staffing shortages
* Operational anomalies

---

## PCA Analysis

Principal Component Analysis (PCA) was applied to:

* Reduce data dimensionality
* Improve visualization
* Identify hidden utilization patterns
* Support clustering analysis

---

## Clustering Analysis

## Algorithm Used

K-Means Clustering

## Segments Identified

### Cluster 0

Low Resource Utilization

## Cluster 1

Medium Resource Utilization

## Cluster 2

High Resource Utilization

This segmentation helps identify departments and periods requiring additional attention.

---

## Machine Learning Model

## Model Used

Random Forest Regressor

## Target Variable

* Maximum Occupancy

## Input Features

* Patients Admitted
* Average Stay
* Staff Count
* Satisfaction Score

## Evaluation Metrics

* Mean Absolute Error (MAE)
* R² Score

The model predicts occupancy levels and supports hospital resource planning.

---

## Visualizations

* Weekly Admission Trends
* Occupancy Trends
* Department-wise Analysis
* Staff Utilization Analysis
* Cluster Analysis
* Anomaly Detection Insights

## Dashboard Objectives

* Monitor hospital performance
* Track resource utilization
* Identify bottlenecks
* Support operational decision-making

---

## Key Insights

* ICU and Emergency departments experienced the highest occupancy levels.
* Patient admissions significantly impacted bed utilization.
* Staff shortages were observed during peak admission periods.
* Anomaly detection identified unusual workload weeks.
* Clustering revealed distinct utilization groups.
* Machine Learning successfully predicted occupancy levels.

---

## Conclusion

This project demonstrates the application of Data Analytics and Machine Learning in healthcare resource management.

The analysis helped identify operational bottlenecks, staffing challenges, and occupancy trends. By leveraging EDA, PCA, Clustering, Anomaly Detection, and Predictive Modeling, the project provides valuable insights that can improve hospital efficiency, optimize resource allocation, and enhance patient care.

---

## Future Enhancements

* Real-Time Hospital Monitoring Dashboard
* Occupancy Forecasting System
* AI-Based Staff Recommendation Engine
* Resource Optimization Framework
* Integration with Hospital Management Systems

---

## Author

**Simran Bhadouria**

Aspiring AI-ML | Business Analyst | Data Analyst

## Skills

* Python
* SQL
* Excel
* Machine Learning
* Data Visualization
* Statistical Analysis

---
