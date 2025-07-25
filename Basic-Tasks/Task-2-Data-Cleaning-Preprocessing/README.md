# Task 2: Data Cleaning and Preprocessing 🧼📊

As part of my Data Science Internship at **Codveda Technologies**, this task focused on preparing raw data for analysis and modeling using real-world techniques.

## 📂 Dataset
- Titanic dataset ([source](https://www.kaggle.com/c/titanic/data))
- Loaded via GitHub into pandas

## ✅ What I Did
- **Handled Missing Data**:
  - Age: filled with median
  - Embarked: filled with mode
  - Dropped high-missing columns: Cabin, Ticket
- **Removed Outliers**:
  - Fare and Age columns using the IQR method
- **Encoded Categorical Variables**:
  - Used One-Hot Encoding for `Sex` and `Embarked`
- **Normalized Numeric Columns**:
  - Used Min-Max Scaling on Age, Fare, SibSp, Parch

## 🧰 Tools Used
- Python
- pandas
- scikit-learn
- Jupyter Notebook

## 📁 Output
- Cleaned CSV: `titanic_cleaned_normalized.csv`
- Notebook: `titanic_preprocessing.ipynb`

---

> #CodvedaJourney #CodvedaProjects #CodvedaExperience #DataCleaning #Pandas #Preprocessing #Normalization
