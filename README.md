# SPARCS Descriptive 2022

## Project Overview
This project analyzes a subset of the **2022 SPARCS (Statewide Planning and Research Cooperative System)** de-identified dataset. The goal of the project is to explore trends in healthcare admissions, patient demographics, and hospital performance metrics through **descriptive statistics** and **data visualizations**. The analysis focuses on key fields such as **Age Group**, **Gender**, **Length of Stay**, **Total Charges**, **Total Costs**, and **Type of Admission**.

The results provide insights into healthcare trends such as:
- The distribution of hospital stays and charges across different age groups and admission types.
- Variations in total costs/charges by demographic factors.
- Key patterns and outliers.

## Dataset
The dataset used in this project is a de-identified subset of the **2022 SPARCS Hospital Inpatient Discharges** dataset. Key fields used in the analysis include:
- **Age Group**
- **Gender**
- **Length of Stay**
- **Total Charges**
- **Total Costs**
- **Type of Admission**
- **Ethnicity**
- **Race**

## Objectives
1. **Descriptive Statistics**: Calculate basic statistics for key numerical fields, such as:
   - Mean
   - Median
   - Standard Deviation
   - Min/Max
   - Quartiles and Percentiles
2. **Exploring Categorical Variables**: Analyze the distribution of categorical fields such as Age Group, Gender, and Type of Admission.
3. **Data Visualizations**: Create visualizations to highlight trends, such as:
   - Histogram of Length of Stay
   - Boxplot of Total Charges
   - Bar plot of Type of Admission
4. **Handling Missing Data**: Identify and handle missing values in key fields.
5. **Summary Report**: A brief summary of findings, focusing on noticeable trends in admissions and charges.

## Analysis Summary
Key findings from the dataset include:
- **Average Length of Stay**: 5.73 days.
- **Total Charges**: Wide variability with a mean of $185548.13 and a median of $795.16.
- **Trends by Age Group**: Younger patients tend to have higher total charges.
- **Trends by Admission Type**: 'Not Available' admissions incur the highest costs, followed closely by Urgent and Newborn admissions.
- **Demographic Disparities**: Analysis reveals differences in total charges based on demographic factors such as gender.

For more details, see the [notebook](SPARCS_Descriptive_2022.ipynb).

## Visualizations
This analysis includes several visualizations to support the findings (including but not limited to):
- **Histogram**: Shows the distribution of Length of Stay.
- **Boxplot**: Highlights outliers in Total Charges.
- **Bar Plots**: Display the distribution of admission types and variations in costs by demographic factors such as age group.

## Conclusion
The analysis provides useful insights into hospital admissions and healthcare charges in the 2022 SPARCS dataset. The trends identified can support decision-making in healthcare policies and hospital resource allocation, particularly in areas such as emergency care and services for older patients.
