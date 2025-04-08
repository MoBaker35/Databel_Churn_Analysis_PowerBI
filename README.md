# Databel_Churn_Analysis_PowerBI
Databel Churn Analysis using Power BI

## Overview

This repository contains the analysis of customer churn using Power BI. The project demonstrates the steps taken to analyze and visualize customer churn data, gain insights into customer behavior, and help identify factors contributing to churn in a given dataset. It utilizes various Power BI features such as data cleaning, transformations, and advanced visualizations to provide a comprehensive churn analysis.

## Project Goals

- Perform data cleaning and transformation on the customer churn dataset.
- Build interactive and insightful dashboards for customer churn analysis.
- Identify key metrics and factors contributing to churn.
- Visualize customer behavior, churn rates, etc.
- Provide actionable insights that can be used for improving retention strategies.

## Dataset

The dataset used in this analysis is a fictional customer churn dataset that contains customer details, such as:

- Customer ID
- Tenure
- Contract type
- Monthly charges
- Total charges
- Payment method
- Customer Local and International calling and data consumption
- Churn status (whether the customer has churned or not)

## Key Features of the Power BI Analysis

1. **Data Cleaning and Transformation:**
   - Import and clean the data (handling missing values, duplicates, and data type corrections).
   - Transform data into useful formats (e.g., calculating churn rate, customer tenure, etc.).
   
2. **Exploratory Data Analysis (EDA):**
   - Analysis of basic statistics (e.g., mean) to understand customer behavior.
   - Distribution of churn rates based on various customer attributes (e.g., payment methods, contract types).
   
3. **Churn Prediction Insights:**
   - Identification of key features contributing to churn (e.g., contract type, monthly charges).
   - Visualization of churn patterns over time, segmented by different customer attributes.

4. **Interactive Dashboards:**
   - Interactive Power BI dashboard showcasing:
     - Churn rate by different customer segments.
     - Churn analysis based on customer demographics (e.g., age, region, service type).
   
5. **Data Visualizations:**
   - Bar charts, line graphs, pie charts, and maps to explore churn data.
   - Use of slicers to filter data dynamically based on different metrics.

## Steps to Reproduce the Analysis

### Prerequisites

To run this analysis, you need to have the following installed on your machine:

- **Power BI Desktop** (latest version) – [Download here](https://powerbi.microsoft.com/)
- **Churn dataset** (CSV or Excel file, provided in the repository or linked above).

### Instructions

1. **Clone the repository:**

     Data is copyright protected but can be found on the internet.

2. **Load the data into Power BI:**
   - Open Power BI Desktop.
   - Click on *Get Data* and select the appropriate file format (CSV, Excel).
   - Load the customer churn dataset into Power BI.

3. **Data Cleaning:**
   - In the *Transform Data* section, apply necessary transformations like:
     - Removing duplicates.
     - Filling missing values or replacing nulls.
     - Changing data types where necessary (e.g., dates, numeric fields).
   
4. **Create Visualizations:**
   - Use Power BI's drag-and-drop functionality to create the following charts:
     - Churn rate by contract type and payment method.
   
5. **Publish the Dashboard:**
   - Save your Power BI file (.pbix) and publish it to the Power BI Service for sharing and collaboration.

## Example Visuals

- **Churn by Contract Type:** A pie chart showing the percentage of churned vs. retained customers based on contract type.
- **Churn Rate against Age Groups:** A clustered column graph displaying churn trends against different age groups.
- **Churn State Map:** A map visualizing churn rates distributed over states.

## Insights and Conclusion

- **High Churn Rate in Month-to-Month Contracts:** Customers with month-to-month contracts have a significantly higher churn rate compared to those with one-year or two-year contracts.
- **Churn Correlated with High Monthly Charges:** Customers with higher monthly charges show a slightly higher churn rate, indicating the importance of pricing and retention strategies.

These insights can help organizations focus on customer retention strategies such as offering incentives, reducing monthly charges, or improving contract terms.

## Conclusion

This Power BI analysis provides valuable insights into customer churn, helping businesses better understand their customer base and make data-driven decisions to reduce churn and improve retention. The dashboards and reports generated through this analysis can be used by business analysts, product managers, and decision-makers for strategic planning.

## Files in this Repository

- **Churn Analysis.pbix** - Power BI report file.
- **Databel Churn Analysis.pdf** - PDF file of Power BI extract (can be viewed in case Power BI not installed)
- **README.md** - Project overview and instructions.
