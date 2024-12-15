# HR Data Analysis and Dashboard

![HR Data analysis_page-0001](https://github.com/user-attachments/assets/dcc6856b-b375-4223-9c50-29536bcce2eb)


## Project Overview
This project focuses on analyzing HR data to uncover patterns and insights about employee attrition, performance, and satisfaction. It demonstrates the use of **Power BI** to visualize key HR metrics and provide actionable insights for better workforce management and decision-making.

### Key Features:
- Data cleaning and transformation tailored for HR analytics.
- Interactive dashboards visualizing employee demographics, attrition trends, and satisfaction levels.
- Insights into performance, job involvement, and work-life balance.

---

## Table of Contents
1. [Objective](#objective)
2. [Tools and Technologies Used](#tools-and-technologies-used)
3. [Data Description](#data-description)
4. [Step-by-Step Workflow](#step-by-step-workflow)
5. [Visualizations in Power BI](#visualizations-in-power-bi)
6. [Files in Repository](#files-in-repository)

---

## Objective
To analyze and visualize HR data, enabling insights into:
- Total employee attrition and its correlation with key factors.
- Employee satisfaction levels across various metrics.
- Demographics and their impact on employee turnover.

---

## Tools and Technologies Used

| **Tool**         | **Purpose**                               |
|-------------------|-------------------------------------------|
| **Power BI**      | Data transformation and interactive visualization |


---

## Data Description
The dataset includes key HR metrics, such as:
- **Employee ID**: Unique identifier for each employee.
- **Department**: Department in which the employee works.
- **Job Role**: Specific role of the employee.
- **Attrition**: Indicates whether the employee left the organization.
- **Age**: Age of the employee.
- **Monthly Income**: Salary of the employee.
- **Job Involvement**: Level of involvement in their job.
- **Satisfaction Ratings**: Ratings for job, relationship, and environmental satisfaction.
- **Work-Life Balance**: Rating of work-life balance.
- **Performance Rating**: Performance evaluation.

---

## Step-by-Step Workflow

### **1. Data Cleaning and Transformation**
- **Objective**: Prepare the dataset for analysis.
- **Key Steps**:
  - Imported the dataset into Power BI using the **Get Data** feature.
  - Renamed columns for clarity and consistency.
  - Removed duplicates and handled missing values.
  - Grouped satisfaction ratings and performance levels into meaningful categories (e.g., "High" and "Low").
  - Created calculated columns for metrics such as attrition rate and satisfaction levels.

### **2. Data Visualization**
- **Objective**: Create interactive and insightful dashboards.
- **Key Visualizations**:
  - **Employee Demographics Overview (Page 1)**:
    - Summarized department-wise and job role-wise distribution using bar charts.
    - Displayed total employees and attrition counts using card visuals.
  - **Attrition Analysis (Pages 2 & 3)**:
    - Attrition by department, job role, and marital status using bar charts.
    - Attrition trends by age and gender using grouped visuals.
  - **Satisfaction and Work-Life Balance (Page 4)**:
    - Satisfaction levels across environmental, relationship, and job metrics using column charts.
    - Work-life balance trends grouped by attrition status.
  - **Performance Metrics (Page 5)**:
    - Correlation between performance ratings and attrition.
    - Monthly income distribution by job role and its impact on turnover.

### **3. Interactivity**
- **Filters and Slicers**:
  - Added filters for department, job role, and gender.
  - Slicers enable detailed exploration of specific attributes.

---

## Visualizations in Power BI
### Dashboard Highlights:
- **Attrition Trends**: Understand key factors driving employee turnover.
- **Satisfaction Insights**: Evaluate employee satisfaction and its role in retention.
- **Workforce Demographics**: Gain insights into the workforce composition.
- **Interactive Exploration**: Use slicers and filters to customize analysis.

![HR Data analysis_page-0001](https://github.com/user-attachments/assets/9e02b7b0-9b62-4b07-96e3-ea8323436eef)


---



## Files in Repository

| **File Name**                  | **Description**                                              |
|--------------------------------|--------------------------------------------------------------|
| `hr_data.csv`                  | Raw dataset used in the project.                            |
| `HR_Analytics_Dashboard.pbix`  | Power BI file containing the final dashboard.               |


