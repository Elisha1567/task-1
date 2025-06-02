# task-1
Welcome! This repository contains my solution for Task 1 of the Data Analyst Internship: cleaning and preparing a raw dataset using Excel. The goal was to deliver a high‑quality, analysis‑ready dataset plus a concise summary of the cleaning steps.
### Data Cleaning Summary – marketing_campaign.csv

- Removed 5 duplicate records using Excel’s "Remove Duplicates".
- Handled missing values:
  - Replaced missing `Income` with column average.
  - Filled missing `Education` with “Unknown”.
- Standardized text values:
  - Fixed inconsistent values in `Marital_Status`.
  - Applied proper casing to `Education` and other categorical fields.
- Converted all date fields (`Dt_Customer`) to `dd-mm-yyyy`.
- Renamed columns to lowercase, snake_case format (e.g., `Year_Birth` → `year_birth`).
- Verified data types:
  - Ensured numeric fields were in correct number format.
  - Confirmed `Dt_Customer` was recognized as a date.

Repository Structure

Path

Description

marketing_campaign.csv

Original raw dataset (Customer Personality Analysis)

cleaned_marketing_campaign.xlsx

Final cleaned file produced in Excel

notebook_preview.ipynb (optional)

Quick Python preview used only to inspect the data

README.md

This document
Cleaning Workflow (Excel)

Step

Action

Excel tool / formula

1

Removed duplicates

Data → Remove Duplicates

2

Handled missing values

Income: filled with median; Education & Marital_Status: replaced blanks with “Unknown”

3

Standardised text

Education, Marital_Status: PROPER(), TRIM(), Find & Replace (e.g. YOLO, Absurd → Single)

4

Converted dates

Dt_Customer: formatted to yyyy‑mm‑dd; verified as numeric date serials

5

Renamed columns

All headers → snake_case, no spaces (e.g. Year_Birth → year_birth)

6

Verified data types

Numeric fields set to Number; dt_customer set to Date
[cleaned_marketing_campaign.xlsx](https://github.com/user-attachments/files/20553318/cleaned_marketing_campaign.xlsx)

![image](https://github.com/user-attachments/assets/e233cb56-b08e-4590-a9dc-893984169dd7)








