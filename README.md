# Employee Data Analysis – ABC Company

## 1. Project Overview
This project analyzes employee data from ABC Company, consisting of **458 rows and 9 columns**.  
The objective is to clean and preprocess the data, perform targeted analyses, and create visual representations that highlight workforce structure and salary distribution.

---

## 2. Dataset Information
- **Rows:** 458  
- **Columns:** 9  

**Key Attributes:**
- **Team:** Name of the Team  
- **Number:** Employee ID  
- **Position:** Designation of the employee  
- **Age:** Age of the employee  
- **Height:** Height of the employee  
- **Weight:** Weight of the employee  
- **College:** College attended by the employee  
- **Salary:** Annual salary of the employee  

---

## 3. Preprocessing
1. **Height Correction** – Replaced incorrect values with random numbers between 150–180 cm.  
2. **Data Cleaning** – Handled missing values using the backward fill (bfill) method.  

---

## 4. Analysis Tasks & Visualizations

### 4.1 Employee Distribution by Team
- Counted the number of employees in each team.  
- Calculated their percentage contribution to the total workforce.  

**Visualizations:**  
- Bar Chart: Employee count for each team  
- Pie Chart: Percentage share of employees per team  

---

### 4.2 Employee Segregation by Position
- Grouped employees by their job positions.  

**Visualizations:**  
- Pie Chart: Percentage of employees across different positions  
- Bar Chart: Count of employees in each position  

---

### 4.3 Predominant Age Group
- Created age groups: *0–29, 30–39, 40–49, 50–59, 60+*  
- Identified the most frequent (predominant) age group.  

**Visualization:**  
- Histogram: Distribution of employees across age groups  

---

### 4.4 Highest Salary Expenditure (Team & Position)
- Grouped salary data by Team and Position.  
- Identified the team–position combination with the maximum salary spend.  

**Visualization:**  
- Bar Chart (with hue): Shows salary expenditure by position for each team  

---

### 4.5 Relation Between Age and Salary
-Find the relation  between age and salary.  

**Visualization:**  
- Scatter Plot: Shows the relationship between Age and Salary  

---

## 5. Key Insights (Data Story)
1. Each team consists of multiple positions, reflecting a diverse workforce.  
2. Most teams have a fairly balanced number of employees, with only slight variations.  
3. The predominant age group is **0–29 years**, which forms the majority workforce and shows relatively higher average salaries.  
4. Salary expenditure is highest for the **SF position in the Los Angeles Lakers team**.  
5. There is a moderate relationship between age and salary — **mid-aged employees tend to earn more**.  

---

These insights can support **strategic workforce planning** and **salary management decisions**.

