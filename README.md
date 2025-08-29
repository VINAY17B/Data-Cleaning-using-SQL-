# 🧹 Data Cleaning using SQL (MySQL Workbench)

## 📖 Project Overview
This project focuses on cleaning and preparing a dataset of company layoffs using **MySQL Workbench**.  
The goal was to ensure the dataset was accurate, consistent, and ready for analysis.

## 📂 Dataset
- Source: Layoffs dataset (publicly available online)
- Rows: Multiple (raw unclean data)

## 🛠 Tools & Skills
- MySQL Workbench
- SQL Queries
- Data Cleaning & Transformation

## 🔑 Steps Performed
1. **Remove Duplicates**  
   - Created staging tables and used `ROW_NUMBER()` to identify and remove duplicates.  

2. **Standardize Data**  
   - Trimmed unnecessary spaces.  
   - Standardized industries (e.g., all “crypto” → “Crypto”).  
   - Fixed inconsistent country names (e.g., `United States.` → `United States`).  
   - Converted date column into `DATE` format.  

3. **Handle Null Values**  
   - Imputed missing industries using company information.  
   - Removed records with NULL `total_laid_off` and `percentage_laid_off`.  

4. **Drop Unnecessary Columns**  
   - Removed helper columns like `row_num`.  

## 📊 Key Insights
- A clean, consistent dataset was created.  
- Prepared for downstream analysis such as layoffs trends, industry comparison, and country-level analysis.  

## 🖼️ Results
 
![Data Cleaning Process]<img width="1010" height="471" alt="image" src="https://github.com/user-attachments/assets/6946b2e5-be6d-416a-81a4-2c5729bfea82" />
<img width="1217" height="442" alt="image" src="https://github.com/user-attachments/assets/328a4149-9dc9-485c-843f-688d993b01da" />



---
