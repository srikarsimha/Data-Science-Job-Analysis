# Job Market Analysis

This repository contains Python scripts for analyzing job market data. The data used for analysis is stored in a CSV file named `jobs.csv`. The analysis includes various visualizations to gain insights into different aspects of the job market.

## Dataset Overview

The dataset `jobs.csv` contains information about job listings, including job category, job title, salary, experience level, employee residence, work setting, company size, and work year.

## Analysis and Visualizations

### 1. Job Categories Ratio

- Pie chart representation of the distribution of job categories.
- Includes the top 5 job categories and aggregates the rest into an "Others" category.

### 2. Experience Level Ratio

- Pie chart representation of the distribution of experience levels required for jobs.

### 3. Countries with Most Number of Employees

- Pie chart representation of the countries with the most number of employees.
- Includes the top 5 countries and aggregates the rest into an "Others" category.

### 4. Top 10 Jobs and Their Average Salaries

- Bar graph showing the average salary for the top 10 job categories.
- Uses Plotly Express for an interactive visualization.

### 5. Number of Unique Job Titles for Each Job Category

- Bar graph showing the number of unique job titles for each job category.

### 6. Salary Growth Over the Years by Job Category

- Line graph showing the change in average salary over the years (from 2020 to 2023) for each job category.

### 7. Top 20 Job Titles by Count

- Bar graph showing the count of the top 20 job titles.

### 8. Count of Employees by Work Setting and Company Size

- Grouped bar plot showing the count of employees by work setting and company size.

### 9. Top 10 Countries by Count of Employees

- Bar graph showing the top 10 countries by the count of employees.

### 10. Employee Density Map by Country (Top 10)

- Choropleth map showing the density of employees by country for the top 10 countries.

### 11. Density of Companies by Country and Company Size

- Choropleth map showing the density of companies by country and company size.

### 12. Average Salary by Country

- Choropleth map showing the average salary by country.

## How to Use

1. Clone the repository to your local machine.
2. Ensure you have Python installed along with the necessary libraries mentioned in the `requirements.txt` file.
3. Run the Python scripts to perform analysis and generate visualizations.
