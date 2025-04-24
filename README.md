# 🚢 Titanic Dataset - Data Cleaning & Preprocessing

This project is part of the AI & ML Internship (Task 1). It focuses on cleaning and preparing the Titanic dataset for machine learning.

---

## 🧠 Task Objective

To understand and apply basic data preprocessing techniques:
- Handling missing values
- Encoding categorical variables
- Feature scaling (normalization/standardization)
- Outlier detection and removal

---

## 📁 Files Included

- `Titanic-Dataset.csv` – Original raw dataset
- `Cleaned_Titanic.csv` – Final cleaned version of the dataset
- `Titanic_Cleaning.ipynb` – Jupyter notebook with full code and steps

---

## ⚙️ Steps Performed

1. **Loaded and explored** the dataset to understand structure and missing values.
2. **Handled nulls**:
   - Filled `Age` with the median
   - Filled `Embarked` with the mode
   - Dropped `Cabin` (too many missing values)
3. **Encoded**:
   - Converted `Sex` using label encoding
   - One-hot encoded `Embarked`
4. **Normalized** `Age` and `Fare` using `StandardScaler`
5. **Visualized** outliers with a boxplot
6. **Removed** rows with extremely high `Fare` values (Fare > 300)
7. **Saved** the cleaned dataset

---

## 🛠 Tools Used

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

## 📬 Submission Info

This project was submitted as part of the internship task.  
🔗 [Submit Here](https://forms.gle/8Gm83s53KbyXs3Ne9)

---

## 🧑‍💻 Author

Harini

