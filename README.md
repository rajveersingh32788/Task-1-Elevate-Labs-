# Netflix Dataset – Data Cleaning & Standardization (Excel)

## 📌 Project Overview
This project focuses on cleaning and standardizing a real-world messy dataset using **Microsoft Excel / Google Sheets**.  
The objective is to convert raw data into a clean, structured format suitable for analysis by following professional data analyst practices.

**Dataset Used:** Netflix Movies and TV Shows  
**Rows:** ~8,000  
**Tools:** Microsoft Excel / Google Sheets

---

## 🛠 Tools & Technologies
- Microsoft Excel / Google Sheets  
- Excel functions: `TRIM`, `UPPER`, `PROPER`
- Filters & Conditional Formatting
- Remove Duplicates
- CSV & Excel export

---

## 📂 Files Included
- **Raw_Data.xlsx** → Original dataset (first 8000 rows, unmodified)
- **Cleaned_dataset.xlsx** → Cleaned and standardized dataset
- **cleaned_dataset.csv** → CSV version of cleaned data for further analysis

---

## 🔍 Data Cleaning Steps Performed

### 1️⃣ Raw Data Handling
- Downloaded dataset in CSV format and opened it in Excel
- Verified correct column headers and delimiters
- Froze header rows and enabled filters on all columns

### 2️⃣ Missing Values
- Identified missing values using filters
- Reviewed column context before taking action
- Retained missing values where removal could impact data integrity

### 3️⃣ Duplicate Records
- Checked for duplicate records using key columns (e.g., title)
- Created a backup of raw data before removal
- Removed exact duplicate entries safely

### 4️⃣ Text Standardization
- Removed extra spaces using `TRIM`
- Standardized text casing using `UPPER` and `PROPER`
- Ensured consistent naming across categorical columns

### 5️⃣ Data Type Validation
- Validated date columns and corrected invalid formats
- Ensured numeric columns contained only numeric values
- Reviewed categorical columns for spelling inconsistencies

### 6️⃣ Cleaned Data Output
- Created a separate cleaned dataset to maintain raw vs processed data separation
- Added a **Data_Quality_Notes** column to document data quality observations
- Exported the final cleaned data as Excel and CSV files

---

## ✅ Final Outcome
- Successfully cleaned and standardized a real-world dataset
- Maintained professional separation between raw and cleaned data
- Produced an analysis-ready dataset suitable for reporting and further analysis

---

## 📤 Submission
This repository is created as part of an internship task submission to demonstrate practical data cleaning skills using Excel and spreadsheet tools.
