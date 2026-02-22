# 📊 Project Management Data Analysis (Python Capstone)

## 📌 Project Overview
This project focuses on analyzing project management data using Python. The objective is to clean, merge, and analyze structured datasets to generate meaningful business insights. The project demonstrates practical data manipulation techniques used in real-world business analytics scenarios.

---

## 🎯 Objectives
- Perform data cleaning and handle missing values  
- Apply statistical techniques for cost imputation  
- Merge multiple datasets using primary keys  
- Conduct group-wise aggregation and cost analysis  
- Generate structured insights from consolidated data  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- NumPy  
- Jupyter Notebook  

---

## 📂 Dataset Description

### 1️⃣ Project Dataset
- Project ID  
- Project Name  
- Cost  
- Status  

### 2️⃣ Employee Dataset
- Employee ID  
- Name  
- Gender  
- City  
- Age  

### 3️⃣ Designation Dataset
- Employee ID  
- Designation  
- Level  

---

## 🔎 Key Operations Performed
- Detection and treatment of missing values  
- Expanding mean technique for replacing missing project cost  
- Data merging using `pd.merge()`  
- Aggregation using `groupby()`  
- Employee-level total project cost calculation  
- Structured final dataset creation  

## 📸 Project Workflow & Key Outputs

### 1️⃣ Initial Project DataFrame  
Creation of structured dataset with identified missing cost values.  
![Initial Dataset](Visuals/initial_project_dataframe.png.png)

### 2️⃣ Missing Value Imputation  
Replacement of missing project costs using expanding mean technique.  
![Missing Value Imputation](Visuals/Missing%20value%20imputation%20using%20expanding%20mean.png)

### 3️⃣ Feature Engineering  
Splitting full name into first and last name for structured data processing.  
![Feature Engineering](Visuals/Name%20split%20feature%20engineering.png)

### 4️⃣ Final Merged Dataset  
Integration of project, employee, and designation datasets using left joins.  
![Merged Dataset](Visuals/Final%20merged%20dataset%20–%20project%20+%20employee%20+%20designation.png)

### 5️⃣ Business Rule Implementation  
Bonus calculation applied to employees with completed projects.  
![Bonus Logic](Visuals/Bonus%20calculation%20–%20business%20rule%20logic.png)

### 6️⃣ Final Cost Aggregation  
Total project cost calculated per employee using groupby aggregation.  
![Final Aggregation](Visuals/Final%20cost%20aggregation%20per%20employee%20–%20groupby%20result.png)
- Missing project cost values were handled using statistical imputation  
- Data merging enabled integrated employee-project analysis  
- Group-wise aggregation provided visibility into cost allocation  
- Structured data processing improves business decision-making in project environments  
