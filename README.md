# Clinical-Dataset-Cleaning-From-Raw-Data-to-Insights-1-000-Rows-

This project focuses on the end-to-end cleaning and preprocessing of a clinical dataset containing 1,000 records. The raw data was initially disorganized, with inconsistent formatting, missing demographic values, and unoptimized data types.

The goal was to transform this "dirty" data into a structured, high-integrity format ready for exploratory data analysis (EDA) and financial reporting.

- Standardized inconsistent formatting across all features for a uniform dataset.
- Used Python (gender-guesser) to impute missing demographic data with high accuracy.
- Parsed billing strings into separate currency and amount (float) columns for easier aggregation.
- Engineered a days_waiting feature to measure the interval between booking and appointment dates.
- Re-cast date and financial columns to their appropriate data types for SQL compatibility.
- Standardized missingness by replacing blank strings with NULL for cleaner downstream analysis.


