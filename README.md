# 30-Day Hospital Readmission Analysis

## Project Overview

This project analyzes hospital readmissions among diabetes patients using the UCI diabetes hospital readmission dataset. The goal is to follow the full data science workflow: reviewing prior research, cleaning the data, exploring patterns, building machine learning models, comparing model performance, and communicating the final results.

The main focus is predicting whether a diabetes patient is readmitted to the hospital within 30 days.

## Research Question

Can machine learning models predict 30-day hospital readmission among diabetes patients?

Supporting questions:

* What patient or hospital-related factors appear connected to readmission?
* Which model performs best for predicting 30-day readmission?

## Project Workflow

1. **Literature Review**
   Review previous studies on diabetes readmission prediction and identify common methods, predictors, and research gaps.

2. **Data Preparation**
   Import the raw dataset, inspect variables, handle missing values, clean inconsistent values, and create a cleaned dataset for analysis.

3. **Exploratory Data Analysis**
   Explore the distribution of the target variable, patient characteristics, hospital utilization variables, medications, diagnoses, and possible predictors of readmission.

4. **Modeling**
   Build multiple classification models to predict 30-day readmission.

5. **Model Evaluation**
   Compare models using classification metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

6. **Final Report and Presentation**
   Summarize the full project, including motivation, methods, results, limitations, and conclusions.

## Dataset 

### Source

Dataset: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008) diabetes hospital readmission dataset.

### Data Description

This dataset contains patient encounter records from hospitals and includes demographic, clinical, medication, diagnosis, and utilization-related variables.

## Target Variable

The target variable is hospital readmission status.

Planned target setup:

* Positive class: readmitted within 30 days
* Negative class: not readmitted within 30 days

The target will be transformed into a binary classification outcome for machine learning.

## Repository Structure

```text
30-Day-Hospital-Readmission-Analysis/
│
├── data/
│   ├── diabetic_data.csv
│   ├── IDS_mapping.xlsx
│   └── diabetic_clean.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── reports/
│   ├── literature_review.docx
│   ├── eda.docx
│   ├── modeling.docx
│   ├── model_evaluation.docx
│   ├── final_report.docx
│   ├── presentation_slides.pdf
│   └── video_link.md
│
└── README.md
```

## Methods

This project uses a supervised machine learning approach for binary classification.

Main methods include:

* Data cleaning
* Exploratory data analysis
* Feature preparation
* Classification modeling
* Model comparison
* Model interpretation
* Discussion of limitations and ethical considerations

## Expected Deliverables

By the end of the project, this repository will contain:

* Original and cleaned data files
* Exploratory analysis notebook
* Literature review
* EDA report
* Modeling report
* Model evaluation report
* Final project report
* Presentation slides
* Video presentation link

## Project Status

This project is in progress. Completed files and reports will be added to the repository as each stage of the workflow is finished.
