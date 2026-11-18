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
- Applied class balancing to handle the difference between readmitted and non-readmitted records.
- Tested different classification thresholds to improve recall.

### 4. Power BI Dashboard
Created an interactive dashboard to show:
- Total hospital encounters
- Overall readmission rate
- Readmitted patient count
- Readmission rates by age group, gender, race, and admission type
- Readmission trends based on previous hospital visits and time in hospital
- Primary diagnosis and discharge-related insights

## Model Results

The final Logistic Regression model was evaluated using a classification threshold of 0.4.

| Metric | Result |
|---|---:|
| Precision | 13.78% |
| Recall | 76.66% |
| F1-Score | 23.36% |

The mentor challenge required at least 75% recall for the positive class. The model achieved **76.66% recall**, meeting the required target.

## Tools and Technologies

- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Power BI
- Jupyter Notebook

## Project Files

- `Hospital_Patient_Readmission_Analysis.ipynb` – Python analysis and machine learning work
- `Hospital_Readmission_Analysis.pbix` – Power BI dashboard file
- `Hospital_Readmission_Analysis.pdf` – Exported dashboard report

## Conclusion

Through this project, I explored hospital patient data, identified factors associated with readmission, and developed a Logistic Regression model to predict 30-day readmission.

I also created a Power BI dashboard to make the analysis easier to understand.

This project helped me gain practical experience in data analysis, machine learning, and data visualization.

*Note: This is an academic data analytics project. The model is not intended for clinical decision-making.*
