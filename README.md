# sas-student-performance-analysis

🎓 Student Performance & At-Risk Analysis Using SAS

📌 Overview

This project uses SAS to analyze student academic and attendance data in order to identify at-risk students and generate data-driven recommendations to improve educational outcomes.

🎯 Problem Statement

School systems need to identify students who are at risk of poor academic performance early so that targeted interventions can be implemented to improve student success.

🛠 Tools & Technologies

SAS (PROC IMPORT, DATA Step, PROC MEANS, PROC FREQ, PROC REG)
CSV dataset
Data cleaning and statistical analysis

📊 Dataset Description

The dataset contains student-level data, including:

Attendance rate
Math scores
Reading scores
Socioeconomic status
Student ID

⚙️ Methodology

1. Data Import & Cleaning

Imported raw data into SAS using PROC IMPORT
Removed missing or invalid records to ensure data quality

2. Feature Engineering

Created a new variable risk_flag to identify at-risk students
Defined as:
Attendance < 80%
OR Math score < 70

3. Exploratory Data Analysis

Used PROC MEANS to calculate averages and summary statistics
Used PROC FREQ to analyze distribution of at-risk students

4. Statistical Analysis

Performed regression analysis using PROC REG
Evaluated the relationship between attendance and academic performance

📈 Key Findings
Students with low attendance consistently demonstrated lower academic performance
A significant portion of students were identified as at-risk
Attendance was a strong predictor of student success

💡 Recommendations
Implement an early warning system based on attendance thresholds
Provide targeted academic support for at-risk students
Monitor student performance regularly to ensure timely intervention

📂 Project Structure
sas-student-performance-analysis/
 ├── data/              # Dataset
 ├── sas_code/          # SAS scripts
 ├── outputs/           # Charts and analysis results
 └── README.md
