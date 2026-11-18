# Hospital Patient Readmission Analysis

## About the Project

This project focuses on analyzing hospital patient records to understand why some patients return to the hospital within 30 days after discharge.

The main aim is to identify factors related to patient readmission, build a machine learning model to predict readmission risk, and present the findings through an interactive Power BI dashboard.

This project was completed as part of the Week 3 Data Analytics challenge.

## Dataset

- **Dataset:** Diabetes 130-US Hospitals (1999–2008)
- **Source:** UCI Machine Learning Repository
- **Total Records:** 101,766
- **Total Features:** 50 original features

The dataset contains patient information such as age, gender, admission type, diagnosis, medications, hospital stay duration, and previous hospital visits.

## Work Done

### 1. Exploratory Data Analysis (EDA)
- Checked missing values and data distributions.
- Analyzed patient age groups and gender.
- Studied admission types and discharge information.
- Compared readmission rates based on previous hospital visits and hospital stay duration.

### 2. Correlation Analysis
- Created a correlation matrix and heatmap.
- Identified numerical features associated with readmission.
- Found that previous inpatient visits had the strongest positive correlation with the readmission target among the numerical features analyzed.

### 3. Machine Learning Model
- Used Logistic Regression for readmission prediction.
- Performed data preprocessing and feature encoding.
- Applied class balancing to handle the difference between
