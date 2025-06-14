# 🧼 MJ Mass Shootings — Data Cleaning & Analysis

This project cleans and documents the publicly available dataset from **Mother Jones’ investigation into US mass shootings (1982–2024)**. It builds on the original reporting by journalists such as Mark Follman, Gavin Aronsen, and Deanna Pan.

> 🔗 [Original Source: Mother Jones Mass Shootings Database](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/)

---

## 📂 Repository Overview

This repository contains:

| File/Folder | Description |
|-------------|-------------|
| `mjms_raw.csv` | The raw CSV exported directly from the Mother Jones spreadsheet |
| `mjms_cleaned.csv` | Cleaned and standardized version of the data |
| `mjms_cleaning_script.py` | Python script used to clean the dataset |
| `mjms_analysis.ipynb` | Jupyter notebook for exploratory data analysis (EDA) |
| `data_dictionary.xlsx` | A clear data dictionary defining each column in the cleaned dataset |
| `README.md` | Project documentation (you're reading it!) |

---

## 📊 Project Goals

- Clean and standardize the dataset (dates, missing values, column names, data types)
- Categorize weapon source types
- Improve consistency in mental health and shooter demographic information
- Add geographic structure (split location into `city`, `state`, `latitude`, `longitude`)
- Prepare the data for meaningful visualization and statistical analysis

---

## 🔍 Data Notes

- The original dataset includes mass shootings in the U.S. from **1982 to 2024**, updated by Mother Jones editors and contributors.
- Starting in **2013**, the database only includes incidents with **3 or more fatalities**, in line with a policy change explained [here](https://www.motherjones.com/politics/2012/12/mass-shootings-mother-jones-full-data/#methodology).
- This cleaned dataset preserves the original content but improves structure and usability for data analysis.

---

## 🛠 How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/JA-Acosta/mj_mass_shootings.git
   cd mj_mass_shootings
