# HR Analytics Project

## Project Overview
This project demonstrates how Python, SQL, and Power BI can work together to turn raw HR data into meaningful insights. It covers the full workflow from data cleaning and exploration to database integration and interactive dashboard reporting. The goal is to support data-driven HR decisions with clear analysis and visuals.

---

## Objectives
- Clean and prepare raw HR data for analysis  
- Store structured data in a relational database  
- Explore patterns and relationships through EDA  
- Present insights through an interactive Power BI dashboard  

---

## Workflow

### 1) Data Cleaning (Python)
- Handled missing values and inconsistencies  
- Standardized formats such as dates and names  
- Removed redundant columns and improved structure  
- Exported the cleaned dataset as `HR_Employee_Cleaned_Data.csv`

### 2) MySQL Database Integration
- Created database: `HR_Employee_DB`  
- Designed table schema for HR data  
- Imported cleaned dataset into MySQL for querying  

### 3) Exploratory Data Analysis (EDA)
- Analyzed salary distributions, turnover reasons, and employee trends  
- Explored relationships between satisfaction, performance, and demographics  
- Built visualizations using Pandas, Matplotlib, and Seaborn  

### 4) Power BI Dashboard
- Connected Power BI directly to MySQL  
- Designed an interactive dashboard with custom calculated columns  
- Built visuals for demographics, department performance, turnover, and salary trends  

---

## Problem Statements & Solutions

### Data Cleaning — `HR_Data_Cleaning.ipynb`
**Problem:** Raw HR data contained missing values, inconsistent formats, and unnecessary columns.  
**Solution:** Cleaned, standardized, and structured the dataset for analysis.

### Exploratory Data Analysis — `HR_Analytics_EDA.ipynb`
**Problem:** Needed to uncover patterns and trends in HR metrics.  
**Solution:** Performed statistical analysis and visual exploration of key indicators.

### SQL Database Integration — `HR_Analytics.sql`
**Problem:** Required efficient storage and querying for scalable analysis.  
**Solution:** Built MySQL schema and wrote queries for department stats, salaries, and turnover.

### Dashboard Creation — `HR Dashboard.pbix`
**Problem:** Insights needed to be presented in a simple, interactive format.  
**Solution:** Built a Power BI dashboard connected to MySQL for real-time analysis.

---

## Key Insights
- Departments with the highest employee turnover  
- Relationship between employee satisfaction and performance  
- Salary trends by department and gender  
- Recruitment source effectiveness  
- Tenure distribution and its impact on performance  

---

## Technologies Used
- **Python:** Pandas, Matplotlib, Seaborn  
- **SQL:** MySQL for database management  
- **Power BI:** Interactive dashboard and reporting  

