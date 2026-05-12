# CLINIC-DATASET-CLEANING-1000-ROWS

![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) 
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) 

This project focuses on the end-to-end cleaning and preprocessing of a clinical dataset containing 1,000 records. The raw data was initially disorganized, with inconsistent formatting, missing demographic values, and unoptimized data types.

The goal was to transform this "dirty" data into a structured, high-integrity format ready for exploratory data analysis (EDA) and financial reporting.

- Standardized inconsistent formatting across all features for a uniform dataset.
- Used Python (gender-guesser) to impute missing demographic data with high accuracy.
- Parsed billing strings into separate currency and amount (float) columns for easier aggregation.
- Engineered a days_waiting feature to measure the interval between booking and appointment dates.
- Re-cast date and financial columns to their appropriate data types for SQL compatibility.
- Standardized missingness by replacing blank strings with NULL for cleaner downstream analysis.

**BEFORE:**

<img width="868" height="399" alt="Captura de pantalla 2026-05-10 180540" src="https://github.com/user-attachments/assets/ef2abf84-a4c7-47d1-87a8-95c3993aed4d" />


**AFTER:**

<img width="1045" height="399" alt="Captura de pantalla 2026-05-10 180555" src="https://github.com/user-attachments/assets/dc3996e3-deed-4ab7-80b6-c0021ffe46a6" />


**A GLIMPSE OF THE CODING AND PROCESS:**

<img width="875" height="554" alt="image" src="https://github.com/user-attachments/assets/829d3980-16d3-40c8-af5b-6b1e6a551863" />
<img width="747" height="555" alt="image" src="https://github.com/user-attachments/assets/97d74e7f-17fc-42c1-8912-b65f89061c06" />
<img width="911" height="639" alt="image" src="https://github.com/user-attachments/assets/5e3398b1-8c92-4f19-8210-47d1f2e05dc1" />



