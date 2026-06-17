# Diabetes Hospital Readmission Prediction

## Project Overview

This project develops a complete Data Science pipeline to predict whether a diabetic patient will be readmitted to a hospital within 30 days of discharge.

The project covers data acquisition, preprocessing, feature engineering, exploratory data analysis, visualization, machine learning model development, evaluation, and business insights.

---

## Student Information

**Name:** Mahnoor Yasir

**Student ID:** F2023266580

**Section:** V1

**Course:** Data Science

**Instructor:** Sir Abdul Jamil

**University:** University of Management and Technology (UMT), Lahore

---

## Dataset Information

**Dataset Name:** Diabetes 130-US Hospitals for Years 1999–2008

**Source:** UCI Machine Learning Repository

**Dataset Link:**
https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

### Dataset Statistics

- 101,766 patient encounters
- 130 hospitals
- 10 years of medical records
- 47 original features
- Binary classification problem

### Target Variable

**readmitted_30_days**

- 1 = Patient readmitted within 30 days
- 0 = Patient not readmitted within 30 days

---

## Project Objectives

- Analyze diabetic patient hospital records.
- Identify factors associated with hospital readmission.
- Perform extensive exploratory data analysis.
- Engineer meaningful healthcare-related features.
- Build predictive machine learning models.
- Compare model performance using multiple evaluation metrics.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- UCI ML Repository API
- Google Colab

---

## Data Preprocessing

The following preprocessing steps were performed:

- Missing value analysis
- Handling invalid records
- Duplicate checking
- Feature engineering
- Data type conversion
- Target variable creation

### Engineered Features

- Age Midpoint
- Total Previous Visits
- Medication Change Count
- Primary Diagnosis Group
- Binary Readmission Target

---

## Exploratory Data Analysis

The project contains 33 visualizations including:

- Target Distribution
- Gender Distribution
- Race Distribution
- Age Distribution
- Hospital Stay Analysis
- Medication Analysis
- Diagnosis Analysis
- Missing Value Analysis
- Correlation Heatmap
- Readmission Rate Analysis

---

## Data Science Questions Answered

1. What percentage of patients were readmitted within 30 days?
2. Which age group has the highest readmission rate?
3. Do previous visits increase readmission risk?
4. Which diagnosis group has the highest readmission rate?
5. Does gender affect readmission?
6. How does hospital stay length affect readmission?
7. Which race group has the highest readmission rate?
8. Does insulin status influence readmission?
9. What is the relationship between medication count and readmission?
10. Which features have the strongest correlation with readmission?

---

## Machine Learning Models

The following models were implemented:

### Logistic Regression

- Baseline classification model
- Fast and interpretable

### Decision Tree

- Rule-based model
- Captures nonlinear relationships

### Random Forest

- Ensemble learning approach
- Reduced overfitting

### Extra Trees Classifier

- Randomized ensemble model
- Improved generalization

---

## Model Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Key Findings

- 11.16% of patients were readmitted within 30 days.
- Previous inpatient visits were the strongest predictor.
- Patients aged 20–30 showed the highest readmission rate.
- Medication changes were associated with higher readmission risk.
- Decision Tree performed better at detecting minority-class patients.

---

## Future Improvements

- Apply SMOTE for class balancing.
- Use XGBoost and LightGBM.
- Hyperparameter optimization.
- Advanced feature selection.
- Deploy as a healthcare prediction dashboard.

---

## References

1. UCI Machine Learning Repository
   https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

2. Scikit-Learn Documentation
   https://scikit-learn.org/

3. Pandas Documentation
   https://pandas.pydata.org/

4. Seaborn Documentation
   https://seaborn.pydata.org/

---

## License

This project is developed for academic and educational purposes as part of the Data Science course at UMT Lahore.
