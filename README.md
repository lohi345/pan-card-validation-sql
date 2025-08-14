# PAN Card Validation Project

## 📌 Project Overview
This project demonstrates **real-world data cleaning and validation** using SQL, focusing on **Indian PAN Card numbers**.  
It includes validations for:
- Correct PAN format (5 uppercase letters, 4 digits, 1 uppercase letter)
- Removal of duplicate entries
- Detection of invalid patterns (e.g., repeated characters)
- Handling of missing/NULL values
- Generating summary reports (Valid vs Invalid)

---

## 📂 File Descriptions

| File Name                                               | Description |
|---------------------------------------------------------|-------------|
| [`pan_validation.sql`](pan_validation.sql)             | Main SQL script to validate PAN numbers: checks format, removes duplicates, detects invalid patterns, and generates summary reports. |
| [`sample_data.sql`](sample_data.sql)                   | Sample SQL insert script to populate the database with test PAN numbers. |
| [`PAN Number Validation - Problem Statement.pdf`](PAN%20Number%20Validation%20-%20Problem%20Statement.pdf) | PDF document describing the problem statement and requirements. |
| [`PAN Number Validation Dataset.csv`](PAN%20Number%20Validation%20Dataset.csv) | CSV dataset containing PAN numbers to test the validation script. |
| [`PAN Number Validation Dataset.xlsx`](PAN%20Number%20Validation%20Dataset.xlsx) | Excel version of the dataset for convenience. |
| [`Project_scripts.txt`](Project_scripts.txt)          | Plain text file containing all SQL scripts and commands used in the project. |

---

## 📄 Problem Summary
- Validate Indian PAN card numbers stored in a database.
- Ensure correct PAN format: 5 letters, 4 digits, 1 letter.
- Remove duplicates and handle missing entries.
- Detect invalid patterns (e.g., repeated characters).
- Produce a summary report of valid vs invalid PANs.

---

## 🛠 SQL Format Rules
Valid PAN format:

