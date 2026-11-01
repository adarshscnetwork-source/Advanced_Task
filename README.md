# ShadowFox Data Analyst Internship - Advanced Level Task

## Project Overview
This project fulfills the advanced-level requirements for the ShadowFox Data Analyst Internship. The objective is to build an executive-style dashboard tracking HR Analytics, specifically focusing on employee attrition, workforce trends, and job satisfaction.

## Data Preparation & Transformation
* **Dataset:** Utilized a realistic HR Analytics dataset tracking 300 employees across Sales, Research & Development, and Human Resources.
* **Cleaning:** Checked for missing values, ensured continuous variables (Age, Monthly Income, Years at Company) were correctly formatted, and verified categorical variables (Attrition, Department) were standardized.
* **KPI Selection:** Identified primary metrics necessary for executive decision-making: Overall Attrition Rate, Average Monthly Income, Average Job Satisfaction, and Average Tenure.

## Dashboard Planning & Interactive Hierarchy (Power BI/Tableau)
To provide decision support in a business context, the dashboard is structurally planned with the following visual storytelling elements:
1. **Executive Scorecard (Top):** High-level KPIs including Headcount, Attrition Count, Attrition Rate (%), and Avg Job Satisfaction.
2. **Interactive Filters (Slicers):** Department, Job Role, and Performance Rating to allow drill-down capability.
3. **Attrition by Department (Bar Chart):** Identifying which sectors of the business are losing talent fastest.
4. **Income vs. Attrition (Box Plot/Histogram):** Visualizing if lower compensation correlates directly with higher turnover.
5. **Job Satisfaction Heatmap:** Correlating satisfaction scores (1-4) with attrition status.

## Executive Insights & Business Storytelling
Based on the data exploration, several key insights drive our recommendations:

**1. The "Flight Risk" Profile**
* The data reveals a strong negative correlation between Job Satisfaction and Attrition. Employees reporting a satisfaction score of 1 or 2 have a significantly higher turnover rate. 
* **Recommendation:** Implement mandatory quarterly pulse surveys. HR should mandate immediate retention interviews for any employee scoring a 2 or below.

**2. Compensation Discrepancies**
* Attrition is heavily concentrated among employees with a Monthly Income below $5,000, particularly within the 'Sales Representative' and 'Laboratory Technician' roles.
* **Recommendation:** Conduct a localized market compensation review for entry-level Sales and R&D roles. Adjusting baseline pay for these specific roles may cost less than the acquisition and training costs of replacing them.

**3. Departmental Bottlenecks**
* The Sales department exhibits higher volatility compared to R&D. 
* **Recommendation:** Review the commission and quota structures within the Sales department, as the base salary alone is not retaining talent.
