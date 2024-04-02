# Loan Data Analysis

This repository contains an analysis of loan data obtained from a bank. The dataset provides information about various factors such as income, property details, loan amount requested, and more, for individuals applying for loans.

## Contents

1. **Data Cleaning**:
   - Handled missing values in columns like "Gender," "Income (USD)," "Income Stability," etc., using appropriate methods such as mode imputation, forward filling, and mean imputation.
   - Detected and removed outliers in numerical columns like "Income (USD)," "Loan Amount Request (USD)," and "Property Price" using the Interquartile Range (IQR) method.
   - Converted data types and replaced placeholder values in columns like "Co-Applicant" and "Type of Employment."

2. **Exploratory Data Analysis (EDA)**:
   - Visualized distributions and relationships between variables using histograms, scatter plots, box plots, and count plots.
   - Analyzed income stability, property prices, loan amount requested, gender distribution, and their interrelationships.
   - Identified patterns in loan requests based on the number of dependents, active credit card status, and defaults.

3. **Insights**:
   - Majority of individuals exhibit low income stability, with peaks observed below 20 years of age and above 60 years of age.
   - Property prices show consistent medians across different property types, with prices ranging up to approximately 185k USD.
   - Equal distribution of males and females in the dataset, with similar income distributions and credit score trends.
   - Loan amount requested varies based on income levels, with dense concentrations observed at certain income thresholds.

## Usage

1. **Data Cleaning**:
   - Ensure the dataset is loaded correctly using pandas.
   - Handle missing values appropriately based on the context of each column.
   - Detect and remove outliers using suitable methods to prepare the data for analysis.

2. **Exploratory Data Analysis**:
   - Visualize distributions and relationships between variables using matplotlib and seaborn.
   - Explore patterns and trends in the data to gain insights into borrower characteristics and loan requests.
   - Generate descriptive statistics and visualizations to present findings effectively.

3. **Insights and Recommendations**:
   - Draw actionable insights from the analysis to inform business decisions and strategies.
   - Provide recommendations for improving loan approval processes, targeting specific customer segments, etc.
   - Document key findings and insights in a clear and concise manner for stakeholders' understanding.



## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## Contributors

- Manish Mishra (manishm112005@gmail.com)


