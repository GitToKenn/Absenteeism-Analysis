# 🧑‍💼 Absenteeism Data Cleaning and Preparation Project

This project focuses on cleaning and preparing a simulated HR absenteeism dataset for further analysis. The data originates from a Udemy course and resembles real-world employee absence records with reasons, demographic attributes, and time-based features.

---

## 📁 Project Structure

- `README.md` – Project overview and documentation
- `notebooks/01_data_cleaning.ipynb` – Jupyter Notebook for data cleaning
- `data/absenteeism_dataset_raw.csv` – Original raw dataset
- `data/absenteeism_dataset_cleaned_2025-05-31.csv` – Cleaned dataset ready for analysis

---

## 📊 Dataset Overview

- **Source**: Dummy data from Udemy (possibly adapted from real-world cases)
- **Rows**: 701
- **Target Variable**: `Absenteeism Time in Hours`
- **Key Features**:
  - `Reason for Absence` (ICD-based classification, grouped)
  - `Date`, `Month Value`, `Day of the Week`
  - Demographics: `Age`, `Education`, `Children`, `Pets`
  - Health & Workload: `Body Mass Index`, `Daily Work Load Average`, `Distance to Work`, `Transportation Expense`

---

## 🧹 Cleaning Steps Summary

- Removed the `ID` column (non-analytical)
- Converted `Reason for Absence` into 4 grouped binary columns:
  - Group 1: Physical Illnesses (1–14)
  - Group 2: Pregnancy & Perinatal (15–17)
  - Group 3: General Medical (18–21)
  - Group 4: Administrative / Other (22–28)
- Extracted `Month Value` and `Day of the Week` from `Date`
- Mapped `Education` into a binary feature (0 = Basic, 1 = Higher)
- Verified all rows contain a valid reason and no missing values are present

---

## 📝 Notebook

The full cleaning workflow is documented in [`01_data_cleaning.ipynb`](notebooks/01_data_cleaning.ipynb).

---

## ✅ Next Steps

_To be determined — exploratory and modeling direction will be added after further study._

---

## 📦 Requirements

- Python 3.x
- pandas
- datetime (standard library)

---

## 🛡️ Data Disclaimer

The dataset used in this project is sourced from a Udemy course and is believed to be adapted from real-world absenteeism records. While the data structure and features reflect actual HR analytics use cases, it has likely been anonymised and modified for educational purposes. This ensures a realistic learning experience while preserving data privacy and ethical use.

---

## 📜 License

This project uses synthetic educational data and is shared for learning and portfolio purposes.