Task 1 - Medical Appointment No-Show (Data Cleaning)
📌 Project Overview

This repository contains the cleaned version of the Medical Appointment No-Show dataset from Kaggle.
The dataset records medical appointments in Brazil and indicates whether patients attended their scheduled appointment.

The main objective of Task 1 (Data Analyst Internship – Elevate Labs) was to perform data cleaning and preprocessing using Excel, and prepare the dataset for further analysis.

🗂 Dataset Information

Original dataset columns:

Patient ID

Appointment ID

Gender

Scheduled Day

Appointment Day

Age

Neighborhood

Scholarship

Hypertension

Diabetes

Alcoholism

Handcap

SMS_received

No-show

🛠 Data Cleaning Steps Performed

Removed unnecessary columns:

Dropped Patient ID, Appointment ID, and Handcap as they were not required for analysis.

Gender column:

Replaced M / F with Male / Female.

Date columns (Scheduled Day, Appointment Day):

Standardized format to YYYY-MM-DD.

Age column:

Found one invalid value (-1) → replaced with the median age.

Neighborhood column:

Converted all text to lowercase.

Removed special characters for consistency.

Scholarship column:

Converted 0 → No, 1 → Yes.

Other binary columns (Hypertension, Diabetes, Alcoholism, SMS_received, No-show):

Left unchanged (kept as 0/1 or Yes/No as in original).

Duplicates & nulls:

Removed duplicate rows (if any).

Verified no missing/null values remained.

📊 Deliverables

Cleaned_Medical_Appointment_not shows.csv → final cleaned dataset in CSV format.

📖 Learning Summary

Through this task, I learned:

How to handle nulls, duplicates, and invalid values in real-world datasets.

The importance of standardizing categorical values (e.g., Male/Female, Yes/No).

How to clean date formats for consistency.

The role of data preprocessing as a critical first step before visualization or modeling.

Practical hands-on experience in Excel-based data cleaning.
