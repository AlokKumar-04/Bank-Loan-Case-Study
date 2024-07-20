# Bank Loan Case Study

## Overview

This project involves a comprehensive analysis of a bank loan dataset to understand factors affecting loan defaults and to derive actionable insights for decision-making. The analysis was conducted using Python and its frameworks in a Jupyter Notebook environment.

## Tools and Technologies

- **Python**: The primary programming language used.
- **Pandas**: For data manipulation and analysis.
- **Numpy**: For numerical operations.
- **Matplotlib**: For creating static, interactive, and animated visualizations.
- **Seaborn**: For statistical data visualization.
- **Jupyter Notebook**: For interactive computing and visualization.

## Data Cleaning and Preparation

1. **Initial Examination**: Loaded and examined the dataset structure. Noted significant null values in several columns.
2. **Handling Null Values**:
   - Removed columns with over 50% null values to enhance data quality.
   - Imputed missing values in remaining columns:
     - Used median values for continuous variables (e.g., `AMT_ANNUITY`) to handle outliers.
     - Used mode values for categorical variables (e.g., `NAME_TYPE_SUITE`).

## Exploratory Data Analysis (EDA)

1. **Outliers and Distribution**: Identified and visualized outliers in continuous variables like `AMT_ANNUITY` and `AMT_GOODS_PRICE` using box plots.
2. **Correlation Analysis**: Generated a heatmap to display correlations between numerical variables, highlighting relationships impacting loan repayment.
3. **Categorical Variables Analysis**: Developed the `Tagget_categorical_Uni` function to analyze and plot categorical variables across different target groups (`Payment_Difficulty` and `All_Other`).

## Targeted Analysis

1. **Key Variables**: Analyzed variables such as `AGE_IN_YEARS`, `AMT_INCOME_TOTAL_in_lakhs`, and `OCCUPATION_TYPE` to explore their relationship with loan default status.
2. **Visualizations**: Utilized pair plots and scatter plots to visualize relationships, segmented by the target variable to identify patterns differentiating defaulters from non-defaulters.

## Visualizations

- Created various visualizations including heatmaps, box plots, bar plots, and scatter plots to effectively illustrate findings. These visualizations provided deeper insights into the data and supported the identification of key factors influencing loan defaults.

## Key Findings

1. **Income and Credit Amount**: Observed a notable relationship between credit amount and total income, with distinct patterns between defaulters and non-defaulters.
2. **Demographic Factors**: Analyzed variables such as age, number of family members, and employment years, revealing their potential impact on loan repayment behavior.
3. **Ownership Status**: Gleaned insights into the financial stability of applicants based on their ownership of cars and real estate.

## Recommendations

1. **Targeted Risk Assessment**: Implement refined risk assessment models incorporating key variables like income levels, credit amount, and demographic factors for better default prediction.
2. **Enhanced Data Collection**: Improve data collection methods to minimize missing values and ensure comprehensive applicant information, leading to more accurate analyses.
3. **Policy Adjustments**: Tailor loan policies based on demographic insights to address risks associated with specific applicant profiles, improving overall portfolio quality.

## Conclusion

This project systematically cleaned, analyzed, and visualized data to provide valuable insights into factors influencing loan defaults. The findings pave the way for more informed decision-making and risk management in the banking sector.

---

For any questions or further information, please contact [Your Name].
