# SQL---Medical-History-database

## 🔹 Database Setup
Created and used the Medical_History database.Explored multiple tables including:
- patients
- doctors
- admission
- province_names
Performed SQL operations such as SELECT, UPDATE, JOIN, GROUP BY, ORDER BY, and CASE statements.

## 🧠 Key SQL Problems Solved
# Data Filtering & Retrieval
- Retrieved patient details based on gender, allergies, and name patterns.
- Filtered patients using weight ranges and multiple patient IDs.
- Extracted records where patients were admitted and discharged on the same day.
- Identified patients born within specific decades (1970s).
- Displayed patients with height >160 and weight >70.
# String & Data Transformation
- Combined first and last names into a full name column.
- Converted names using UPPER() and LOWER() functions.
- Sorted names by length and alphabetical order.
- Generated formatted names such as LASTNAME,firstname.
# Data Cleaning & Updates
- Updated NULL allergy values to 'NKA' (No Known Allergies).
- Handled NULL values in allergy analysis.
# Joins & Table Relationships
- Joined patients and province tables to display full province names.
- Linked patients, admissions, and doctors to identify diagnoses and doctor specialties.
- Retrieved patients diagnosed with Dementia or Epilepsy and related doctor information.
# Aggregations & Statistical Insights
- Counted total patients and admissions.
- Calculated male vs female patient counts.
- Found patients admitted multiple times for the same diagnosis.
- Identified cities with the highest patient counts.
- Calculated difference between maximum and minimum patient weights.
- Measured sum of patient heights by province.
# Date & Time Analysis
- Extracted birth years and admission dates.
- Counted how many admissions occurred per day of the month.
- Filtered records based on specific years and decades.
# Advanced SQL Logic
- Created weight groups using FLOOR() for patient categorization.
- Calculated BMI using weight and height and classified patients as obese using CASE statements.
- Used UNION ALL to combine patient and doctor roles into a single dataset.

# ✅ Outcome:
This project strengthened practical SQL skills by solving 30+ real-world healthcare database problems, focusing on data analysis, transformation, and relational database querying.
