# Human Activity Data Analysis

## Overview

Analyzed a 75,000-row sensor dataset to identify human activity patterns.
Compared 6 machine learning algorithms to find the best model for activity
classification, and applied dimensionality reduction to improve efficiency.

-----

## Problem Statement

Sensor data from wearable devices generates massive amounts of raw data.
This project identifies activity patterns and builds a reliable classification
model to support real-time activity monitoring systems.

-----

## Dataset

- *Source:* UCI HAR (Human Activity Recognition) Dataset
- *Size:* 75,000 sensor readings
- *Features:* 561 sensor features (accelerometer & gyroscope)
- *Activities:* Walking, Walking Upstairs, Walking Downstairs, Sitting, Standing, Laying

-----

## Tools & Technologies

- *Language:* Python
- *Libraries:* pandas, NumPy, scikit-learn, Matplotlib
- *Techniques:* Classification, PCA, Feature Engineering, StandardScaler
- *Platform:* Google Colab

-----

## Approach

### 1. Data Quality & Preprocessing

- Loaded 75,000 sensor readings from UCI HAR dataset
- Checked and resolved missing values and duplicate rows
- Standardized features using StandardScaler for model reliability

### 2. Exploratory Data Analysis

- Visualized activity distribution across all 6 activity classes
- Identified patterns in sensor readings per activity

### 3. Model Comparison — 6 Algorithms

Trained and evaluated 6 classification algorithms:

- Logistic Regression
- Random Forest
- Gradient Boosting
- SVM
- KNN
- Decision Tree

### 4. Dimensionality Reduction (PCA)

- Reduced features from 9 → 7 using PCA
- Retained *99.96%* of data variance
- Improved analysis efficiency and reporting clarity

-----

## Results

|Model              |Accuracy  |
|-------------------|----------|
|Logistic Regression|0.6603    |
|*Random Forest*  |*0.9991*|
|Gradient Boosting  |0.8161    |
|SVM                |0.6850    |
|KNN                |0.9770    |
|Decision Tree      |0.9991    |

✅ *Best Model: Random Forest — 99.91% accuracy*
✅ *Features reduced: 9 → 7 (99.96% variance retained)*

-----

## Visual Dashboard

- Activity Distribution bar chart (75,000 rows)
- Model Accuracy Comparison chart (6 algorithms)

-----

## Project Structure


human-activity-analysis/
│
├── Human_Activity_Data_Analysis.ipynb   # Main Colab notebook
├── README.md
└── requirements.txt


-----

## How to Run

1. Clone the repository
   
   bash
   git clone https://github.com/sirishaxx/human-activity-analysis.git
   
1. Open the notebook in Google Colab
1. Run all cells — dataset downloads automatically

-----

## Course Context

*Florida Atlantic University* — Data Science & Analytics | Jan – May 2025

-----

## Author

*Sirisha Gadde*  
MS Computer Science, Florida Atlantic University  
[LinkedIn](https://linkedin.com/in/sirisha-gadde) • [GitHub](https://github.com/sirishaxx)
