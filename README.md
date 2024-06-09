# Data Scientists Salary Analysis

## Overview
This project involves analyzing and visualizing the salaries of data scientists using a dataset. The analysis covers various aspects such as experience level, employment type, job title distribution, and salary trends. Additionally, a machine learning model is implemented to predict salaries based on specific features.

## Dataset
The dataset used for this analysis is `ds_salaries.csv`. It contains the following columns:
- **work_year**: The year in which the salary was reported.
- **experience_level**: The level of experience (e.g., Entry-level, Mid-level, Senior-level).
- **employment_type**: The type of employment (e.g., Full-time, Contract).
- **job_title**: The job title of the data scientist.
- **salary**: The salary of the data scientist in USD.
- **salary_currency**: The currency of the reported salary.
- **salary_in_usd**: The salary converted to USD.
- **company_location**: The location of the company.
- **employee_residence**: The residence of the employee.
- **remote_ratio**: The ratio of remote work.
- **company_size**: The size of the company (e.g., Small, Medium, Large).

## Preprocessing
### Experience Level Conversion
The experience levels were converted to full forms:
- **SE** to **Senior-level**
- **MI** to **Mid-level**
- **EN** to **Entry-level**

### Employment Type Conversion
The employment types were converted to full forms:
- **FT** to **Full-time**
- **CT** to **Contract**
- **PT** to **Part-time**
- **FL** to **Freelance**

## Analysis and Visualization
### Countplots and Boxplots
#### Countplot of Experience Levels
![Experience Levels Countplot](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/6666ee3d-033a-44bc-b2ae-5edd82bcb0bb)

#### Boxplot of Salary vs Experience Level
![Salary vs Experience Level Boxplot](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/ab2a6fa5-21d3-4119-831f-8dd714711e51)

#### Barplot of Mean Salary by Experience Level

### Job Title Distribution
#### Pie Chart Showing the Distribution of the Top 10 Job Titles
![Job Title Distribution Pie Chart](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/3ea53f8d-8897-48c6-bb6d-bb0d87ae9b82)

### Salary Distribution by Location and Range
#### Heatmap Showing the Salary Distribution by Company Location and Range
![Salary Distribution Heatmap](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/b0b05e95-f702-4b1d-a967-e2ee2b81c292)

### Average Salary by Company Size
#### Barplot Showing the Average Salary by Company Size
![Average Salary by Company Size Barplot](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/3cd3a90e-45da-4a25-983d-715ecd84e24a)

### Average Salary by Experience Level and Employment Type
Barplot showing the average salary by experience level and employment type.
![Average Salary by Experience Level and Employment Type Barplot](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/8d93c40a-cf04-4981-a9b4-14b0f6f931e6)

### Salary Trends
Line plots showing median salary trends in the USA and India.
![Salary Trends Line Plots](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/5cdeb64e-02a3-4c2c-9a6b-f998043b0032)

## Machine Learning Model
A Random Forest Regressor was used to predict salaries based on the following features:
- **work_year**
- **experience_level**
- **employment_type**
- **company_size**
- **remote_ratio**

### GUI for Salary Prediction
A GUI was created that allows users to enter the following details:
- Year
- Experience Level
- Employment Type
- Company Size
- Remote Ratio
![GUI for Salary Prediction](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/cf4628af-00f1-4145-958f-707eec9cbc06)

The salary is then predicted based on the Random Forest model.
![Salary Prediction Result](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/cf84b23d-560f-4fb9-94ca-55af701882c6)

### Feature Importance
The important features identified by the Random Forest model are:
1. **experience_level**
2. **company_size**
3. **remote_ratio**
4. **employment_type**
5. **work_year**
![Feature Importance](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/94a3c67f-859c-4b56-8f4f-503ff427a4f2)

### Actual vs Predicted Salaries
Some examples of actual and predicted salaries for random values using the Random Forest model:
![Actual vs Predicted Salaries](https://github.com/Divyam-Padole/Data-Scientist-Salary-Prediction/assets/104207473/735bcce3-fa7f-48aa-802b-88c08519ff52)
