# 🧑‍💼 Absenteeism Data Cleaning and Preparation Project

This project focuses on cleaning and preparing a dummy absenteeism dataset for further analysis. The data originates from a Udemy course and simulates employee absentee records with various reasons, demographics, and time-based features.

---

## 📁 Project Structure

absenteeism-project/
│
├── README.md
├── notebooks/
│ └── 01_data_cleaning.ipynb
├── data/
│ ├── raw/
│ │ └── absenteeism_dataset_raw.csv
│ └── processed/
│ └── absenteeism_dataset_cleaned_2025-05-31.csv


---

## 📊 Dataset Overview

- **Source**: Dummy data from Udemy
- **Rows**: 701
- **Target Variable**: `Absenteeism Time in Hours`
- **Key Features**:
  - Reason for Absence (ICD-based classification)
  - Date, Month, Day of the Week
  - Demographics: Age, Education, Children, Pets
  - Health: BMI, Workload, Distance

---

## 🧹 Cleaning Steps Summary

- Converted categorical reason codes into 4 grouped categories:
  - Group 1: Physical Illnesses (1–14)
  - Group 2: Pregnancy & Perinatal (15–17)
  - Group 3: General Medical (18–21)
  - Group 4: Administrative / Other (22–28)
- Removed ID column
- Mapped education levels into binary (0 = basic, 1 = higher)
- Extracted weekday and month features from the date
- Verified no missing or inconsistent values

---

## 📝 Notebook

The full cleaning process is documented in [`01_data_cleaning.ipynb`](notebooks/01_data_cleaning.ipynb).

---

## ✅ Next Steps

- Exploratory Data Analysis (EDA)
- Regression modeling
- Insight generation

---

## 📦 Requirements

- Python 3.x
- pandas, numpy, matplotlib (see notebook for full list)

---

## 📜 License

This project uses dummy educational data and is shared for learning purposes.


---

## 📊 Dataset Overview

- **Source**: Dummy data from Udemy
- **Rows**: 701
- **Target Variable**: `Absenteeism Time in Hours`
- **Key Features**:
  - Reason for Absence (ICD-based classification)
  - Date, Month, Day of the Week
  - Demographics: Age, Education, Children, Pets
  - Health: BMI, Workload, Distance

---

## 🧹 Cleaning Steps Summary

- Converted categorical reason codes into 4 grouped categories:
  - Group 1: Physical Illnesses (1–14)
  - Group 2: Pregnancy & Perinatal (15–17)
  - Group 3: General Medical (18–21)
  - Group 4: Administrative / Other (22–28)
- Removed ID column
- Mapped education levels into binary (0 = basic, 1 = higher)
- Extracted weekday and month features from the date
- Verified no missing or inconsistent values

---

## 📝 Notebook

The full cleaning process is documented in [`01_data_cleaning.ipynb`](notebooks/01_data_cleaning.ipynb).

---

## ✅ Next Steps

- Exploratory Data Analysis (EDA)
- Regression modeling
- Insight generation

---

## 📦 Requirements

- Python 3.x
- pandas, numpy, matplotlib (see notebook for full list)

---

## 📜 License

This project uses dummy educational data and is shared for learning purposes.
