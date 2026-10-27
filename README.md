# Healthcare Appointment Attendance Analysis using Python

## Project Overview

This project analyzes healthcare appointment data to understand patient attendance and missed appointment patterns. The goal is to identify trends that may help healthcare providers improve appointment management.

## Objectives

- Analyze appointment attendance and no-show rates.
- Explore no-show patterns by gender and age group.
- Compare no-show rates for appointments with and without SMS reminders.
- Examine the relationship between waiting time and missed appointments.
- Analyze appointment counts by weekday.
- Present findings through data visualizations.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Dataset

The project uses the **Medical Appointment No Shows** dataset, which contains patient demographics, appointment dates, health indicators, SMS reminder information, and appointment attendance status.

**Dataset source:** [Medical Appointment No Shows — Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

- Original records: 110,527
- Original columns: 14
- Target column: `No-show`

## Data Cleaning

- Checked the dataset structure, data types, and missing values.
- Checked for duplicate records.
- Removed one record with an invalid negative age.
- Converted appointment and scheduling dates into datetime format.
- Identified and excluded five records with negative waiting times from the analysis.

## Key Findings

- **Total appointments analyzed:** 110,521
- **Attendance rate:** 79.81%
- **No-show rate:** 20.19%
- **Female no-show rate:** 20.31%
- **Male no-show rate:** 19.96%
- **Highest no-show rate by age group:** 18–35 years, at 23.81%
- **Lowest no-show rate by age group:** 56 years and above, at 15.64%
- **No-show rate without SMS reminders:** 16.70%
- **No-show rate with SMS reminders:** 27.57%

These results describe patterns in the dataset and do not prove that SMS reminders cause changes in appointment attendance.

## Visualizations

The project includes six visualizations:

1. Attended vs. missed appointments
2. No-show rate by gender
3. No-show rate by age group
4. Appointment distribution by SMS reminder status
5. No-show rate by waiting time
6. Appointment counts by weekday

## Conclusion

This project demonstrates how Python can be used for data cleaning, exploratory data analysis, visualization, and business insight generation.

The analysis identified patterns in appointment attendance across gender, age groups, SMS reminder status, waiting time, and weekdays. These findings may help healthcare providers investigate appointment scheduling and patient communication strategies.

The analysis identifies associations and patterns in the available data; it does not establish the causes of missed appointments.

## Project Files

- `Healthcare Appointment Attendance Analysis.ipynb` — Notebook containing data cleaning, analysis, and visualizations.
- `appointments.csv` — Dataset used for the analysis, if redistribution is permitted by its licence.

## Author

Pranali Pakere
