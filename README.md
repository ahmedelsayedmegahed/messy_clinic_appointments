# 🏥 Clinic Appointments Data Cleaning & Validation (Excel)

## 📌 Project Overview

This project focuses on cleaning and validating a messy clinic appointments dataset using Microsoft Excel.

The dataset contains patient information, appointment and booking dates, doctor details, medical departments, billing amounts, and follow-up requirements.

The goal is to identify data quality issues, standardize inconsistent values, handle missing data, and improve data consistency to prepare the dataset for future analysis.

---

## 📂 Dataset

- **Original Dataset:** <a href="https://github.com/ahmedelsayedmegahed/messy_clinic_appointments/blob/main/messy_clinic_appointments.csv">Original Dataset</a>
- **Cleaned Dataset:** <a href="https://github.com/ahmedelsayedmegahed/messy_clinic_appointments/blob/main/cleaned_clinic_appointments.xlsx">Cleaned Dataset</a>

### Dataset Overview

- **Total Records:** 1,000
- **Total Columns:** 10
- **Data Type:** Clinic Appointments Data

### Columns Description

| Column | Description |
|---|---|
| `patient_id` | Unique identifier assigned to a patient |
| `patient_name` | Patient's name |
| `age` | Patient's age |
| `gender` | Patient's gender |
| `appointment_date` | Scheduled appointment date |
| `booking_date` | Date the appointment was booked |
| `doctor` | Assigned doctor |
| `department` | Medical department |
| `billing_amount` | Appointment billing amount |
| `follow_up_required` | Indicates whether follow-up is required |

---

## 🛠 Tools Used

- Microsoft Excel
- Excel Functions & Formulas
- Find & Replace
- Sorting & Filtering
- Data Validation

---

## 🧹 Data Cleaning Process

The dataset was examined to identify inconsistencies and common data quality issues.

The cleaning process focuses on the following areas:

- **Missing Values:** Identifying missing entries in the `gender` and `billing_amount` columns and determining the appropriate treatment.
- **Gender Standardization:** Reviewing inconsistent representations such as `M`, `Male`, `male`, `F`, `Female`, and `female`.
- **Date Standardization:** Converting inconsistent date formats in `appointment_date` and `booking_date` into a consistent date format.
- **Billing Amounts:** Reviewing currency symbols, mixed currency representations, and numeric formatting in `billing_amount`.
- **Follow-up Status:** Standardizing values such as `Yes`, `Y`, `No`, and `N`, while investigating numeric representations such as `1` and `0`.
- **Data Type Validation:** Ensuring that columns use appropriate data types for accurate processing and analysis.
- **Data Consistency:** Reviewing values across columns to identify potential inconsistencies.

*Note: The final cleaning steps and treatment of missing or ambiguous values should reflect the actual transformations performed.*

---

## ✅ Data Validation

Data validation is used to check whether the cleaned dataset follows the expected data rules and formats.

The validation process focuses on:

- Checking for missing values in required fields.
- Verifying that patient ages contain valid numeric values within an appropriate range.
- Ensuring appointment and booking dates are stored as valid dates.
- Checking that gender values follow a consistent set of categories.
- Verifying that billing amounts are stored as numeric values after handling currency information appropriately.
- Ensuring `follow_up_required` contains valid and consistent status values.
- Reviewing records for potential duplicates without automatically removing legitimate repeat appointments.

---

## 🖼️ Before & After Comparison

This section presents a visual comparison of the original dataset and the cleaned version to demonstrate the improvements made during data cleaning and validation.

### 🔴 Before Data Cleaning

The original dataset contains inconsistent date formats, different representations of categorical values, missing entries, and mixed currency symbols.

![Before Data Cleaning](Screenshots/Before.png)

### 🟢 After Data Cleaning

The cleaned dataset demonstrates standardized formats, improved consistency, and validated values following the applied cleaning rules.

![After Data Cleaning](Screenshots/After.png)

---

## 📁 Project Structure

```text
Clinic-Appointments-Data-Cleaning/
│
├── Dataset/
│   ├── messy_clinic_appointments.csv
│   └── cleaned_clinic_appointments.xlsx
│
├── Screenshots/
│   ├── Before.png
│   └── After.png
│
└── README.md
```

---

## 🎯 Project Objectives

- Identify common data quality issues in a healthcare-related dataset.
- Clean inconsistent and missing data.
- Standardize date formats and categorical values.
- Improve the consistency of billing and follow-up information.
- Validate data types and values against defined rules.
- Prepare a more reliable dataset for future data analysis.

---

## 🚀 Conclusion

This project demonstrates practical Microsoft Excel skills in data cleaning and data validation using a clinic appointments dataset.

By identifying missing values, inconsistent formats, and potentially invalid entries, the project highlights the importance of data quality and validation in preparing reliable datasets for further analysis.

## 💡 Future Improvements

- Automate repetitive cleaning tasks using Power Query.
- Develop additional data quality checks using Excel formulas.
- Create a data quality summary to track issues before and after cleaning.
- Use the cleaned dataset to build an interactive dashboard in Power BI.
