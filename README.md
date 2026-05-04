# Job-Salary-Prediction-Dataset-Kaggle

📊 Job Salary Prediction (Kaggle Dataset)
📌 Project Overview

This project focuses on analyzing and predicting salaries using a large-scale job dataset. It explores how factors such as location, experience, job role, company size, and education level influence salary outcomes.

The project applies data analysis and machine learning techniques to extract insights and build predictive models.

## Dataset Information
📊 Source: Kaggle
📦 Size: ~250,000 job records
🔗 Dataset Link:
https://www.kaggle.com/datasets/hosan707/job-salary-prediction-dataset/data

## Dataset Features
The dataset includes the following key variables:
1) Job Title
2) Experience Level
3) Education Level
4) Skills Count
5) Certifications
6) Industry
7) Company Size
8) Location
9) Remote Work
10) Salary Range

## Project Workflow
### Data Cleaning
* Handled missing values
* Converted salary ranges into numerical format
* Removed redundant and duplicate features

### Exploratory Data Analysis (EDA)
* Analyzed relationships between:
  ** Experience vs Salary
  ** Skills vs Salary
  ** Job Role vs Salary
* Identified key patterns and trends

### Feature Engineering
* Created new categorical features (e.g., certification levels)
* Transformed variables for better analysis

### Feature Selection
* Used permutation importance to identify key predictors
* Selected most impactful features:
 * Location
 * Experience
 *  Company Size
 * Job Role
 * Education

### Model Building
1) Linear Regression (Baseline Model)
R² Score: 0.96
MAE: ₹5,436

2) Decision Tree Regressor
R² Score: 0.93
MAE: ₹7,497

3) Random Forest Regressor
R² Score: 0.94
MAE: ₹7,184

## Final Conclusion
The analysis reveals that salary prediction in this dataset is largely driven by structured factors such as geography, experience, and job role, with limited non-linear complexity.
Linear Regression performed best, indicating that the underlying relationships are mostly linear.


### Technologies Used
Python 
Pandas & NumPy
Scikit-learn
Matplotlib / Seaborn
Pandas & NumPy

# Author
# Himanshu Kapoor
learn
Matplotlib / Seaborn
