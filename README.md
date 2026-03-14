# SQL Data Cleaning Project – Layoffs Dataset

Author: Sahithi Reddy

## Project Overview
This project focuses on cleaning a real-world layoffs dataset using SQL. 
The data was cleaned using MySQL by removing duplicates, standardizing values, and handling null data.

## Tools Used
- MySQL
- MySQL Workbench
- SQL
- GitHub

## Data Cleaning Steps
1. Created a staging table to work on a copy of the dataset
2. Removed duplicate records using ROW_NUMBER()
3. Trimmed and standardized company names
4. Standardized industry names
5. Cleaned country names
6. Converted the date column to proper DATE format
7. Checked for NULL and blank values
8. Removed helper columns
9. Generated the final cleaned dataset

## Final Query
```sql
SELECT *
FROM layoffs_staging2;
