# 🌟 HR Attrition Dashboard 🌟

This repository contains the data and Tableau workbook for the Employee Attrition Analysis Dashboard. The dashboard provides insights into key performance indicators (KPIs) related to employee attrition, including attrition count, attrition rate, active employees, and average age. It also visualizes data on attrition by age, department, job satisfaction, education, and gender.

## 📋 Table of Contents
- [📊 Data](#data)
- [⚙️ Setup](#setup)
- [🧹 Data Cleaning](#data-cleaning)
- [📈 Tableau Dashboard](#tableau-dashboard)
  - [📌 KPI Creation](#kpi-creation)
  - [🔍 Filters](#filters)
  - [📉 Visualizations](#visualizations)
- [🤝 Contributing](#contributing)
- [📜 License](#license)

## 📊 Data
The dataset consists of 1500 rows and 40 columns. The data is stored in a CSV file.

## ⚙️ Setup
1. Connect the dataset to Tableau using a live connection. If the data becomes too large, use an Extracted connection for better performance.
2. Ensure the dataset is cleaned according to the requirements before creating the visualizations.

## 🧹 Data Cleaning
1. Remove any null or irrelevant data.
2. Standardize data formats (e.g., dates, text fields).
3. Ensure that the data types of columns are correctly assigned (e.g., numerical, categorical).

## 📈 Tableau Dashboard

### 📌 KPI Creation
1. **Attrition Count**: Created a calculated field for the total number of attritions.
2. **Attrition Rate**: Created a calculated field to determine the attrition rate.
3. **Active Employees**: Created a calculated field to count the number of active employees.
4. **Average Age**: Created a calculated field to calculate the average age of employees.

### 🔍 Filters
1. **Education Filter**: Applied a filter on the education field so that it affects all subsequent visualizations.
2. **Multiple Value Drop-down Filter**: Added a filter based on education to focus on highly qualified individuals leaving the company.

### 📉 Visualizations
1. **Attrition by Age**: Created a dual-axis chart with synchronized axes to visualize attrition by age.
2. **Department-wise Attrition**: Created an instance to analyze attrition across different departments.
3. **Number of Employees by Age**: Created a parametric bin to analyze the age group that is leaving the most using a frequency graph.
4. **Job Satisfaction Rating**: Changed job satisfaction values to dimensions and visualized ratings on a scale of 1 to 4.
5. **Education-wise Attrition**: Displayed attrition data in descending order based on education level to understand which level of professionals are leaving.
6. **Attrition Rate by Gender and Age Group**: Analyzed attrition rate by gender across different age groups to provide insights for HR.

### 🔗 Action Filters
Added an action filter to integrate the entire dashboard, allowing selections in one visualization to filter and adjust the remaining visualizations.

## 🤝 Contributing
Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

## 📜 License
This project is licensed under the MIT License. See the LICENSE file for more details.
