# Task 1: Data Cleaning and Preprocessing

# Objective:
Clean and prepare a raw dataset containing missing values, duplicates, inconsistent formats, and incorrect data types.

# Dataset:
- `medical_appointment_no_shows.csv`: Original dataset
- `cleaned_medical_appointments.csv`: Cleaned and preprocessed version

# Tools Used:
- Python (Pandas)

# Steps Performed:
1. Loaded the dataset using pandas
2. Identified and removed missing values
3. Removed duplicate rows
4. Standardized text fields (like gender, no_show)
5. Converted date columns to consistent dd-mm-yyyy format
6. Renamed columns to lowercase and underscore format
7. Fixed data types (e.g., age to int)

# Output:
- Cleaned dataset saved as `cleaned_medical_appointments.csv`

# How to Run:
```bash
python data_cleaning_script.py
