# 🎓 Student Data Cleaning Project – Python & Pandas

This project demonstrates data cleaning and preprocessing using Python and Pandas on a student performance dataset.

## 📂 Project Files

- `student-Rawdataset.csv` → Original raw dataset  
- `student_cleandatas.csv` → Cleaned dataset  
- `Students Data cleaning using pandas.ipynb` → Data cleaning notebook  

---

## 🛠️ Tools Used

- Python
- Pandas
- Jupyter Notebook / VS Code

---

## 🔍 Data Cleaning Steps Performed

- Checked dataset structure using `df.info()`
- Identified missing values using `df.isnull().sum()`
- Removed duplicates
- Cleaned categorical columns (removed spaces, standardized values)
- Filtered invalid age, absences, failures, studytime values
- Converted `passed` column from Yes/No → 1/0
- Exported cleaned dataset to CSV

---

## 📊 Final Output

Cleaned dataset saved as:student_cleandatas.csv
