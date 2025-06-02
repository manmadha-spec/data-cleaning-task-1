<<<<<<< HEAD
# data-cleaning-task-1
=======
# 📊 Task 1: Data Cleaning and Preprocessing

## 🔍 Dataset Used:
**Medical Appointment No Shows**  
Source: [Kaggle](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

This dataset contains information about medical appointments in Brazil and whether patients showed up for their appointments.

---

## 🎯 Objective:
Clean and preprocess the dataset by addressing:
- Missing values
- Duplicate entries
- Inconsistent formatting
- Incorrect data types

---

## 🧰 Tools Used:
- Python
- Pandas

---

## 🔧 Steps Performed:

1. **Renamed Columns**  
   - Converted all column names to lowercase and replaced spaces with underscores.

2. **Checked for Missing Values**  
   - Used `df.isnull().sum()` to verify missing data (none found in this case).

3. **Removed Duplicates**  
   - Used `df.drop_duplicates()` to eliminate any duplicate records.

4. **Standardized Categorical Text**  
   - Converted `gender` values to uppercase using `.str.upper().str.strip()`.

5. **Converted Date Columns**  
   - Changed `scheduledday` and `appointmentday` to datetime using `pd.to_datetime()`.

6. **Fixed Data Types**  
   - Ensured `age` was of type integer.

7. **Saved Cleaned Data**  
   - Exported cleaned dataset to `cleaned_appointments.csv`.

---

## 📁 Files in this Repository:
- `appointments.csv` – Original dataset
- `clean_data.py` – Python script for cleaning
- `cleaned_appointments.csv` – Final cleaned dataset
- `README.md` – Summary of the project

---

## 🧠 Key Learning:
This task helped me gain hands-on experience with real-world data issues and practice common data cleaning techniques using Pandas
747b6ed (Initial commit - cleaned dataset and script added)
