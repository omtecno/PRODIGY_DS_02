# PRODIGY_DS_02  
## Titanic Test Dataset – Exploratory Data Analysis (EDA)

🚢 **Comprehensive exploratory data analysis of the historic Titanic dataset to understand passenger demographics and ticketing patterns from the 1912 disaster.**

---

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Titanic test dataset** using Python.  
The objective is to **clean the data**, **handle missing values**, and **visualize meaningful patterns** related to passenger demographics and ticket fares.

⚠️ **Important Note:**  
This analysis uses the **Titanic test dataset**, which **does NOT contain survival information (`Survived` column)**.  
Hence, the focus is on **demographics and fare-related insights**, not survival prediction.

---

## 📂 Dataset Information
- **Source:** Titanic Test Dataset (Kaggle)
- **Total Records:** 418 passengers
- **Total Features:** 11 columns

### 🔍 Feature Description

| Column | Description |
|------|------------|
| PassengerId | Unique passenger identifier |
| Pclass | Passenger class (1st, 2nd, 3rd) |
| Name | Passenger name |
| Sex | Gender |
| Age | Age of passenger |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation |

---

## 🧹 Data Cleaning Steps
The following preprocessing steps were applied:

- Filled missing **Age** values with the **mean**
- Filled missing **Fare** values with the **median**
- Replaced missing **Cabin** values with `"Unknown"`
- Verified **no duplicate records**
- Ensured **zero remaining null values**

✔ The dataset is now **clean and analysis-ready**.

---

## 📊 Exploratory Data Analysis

### 1️⃣ Age Distribution (Histogram)
- Displays overall passenger age distribution  
- Majority of passengers are aged **20–40 years**

### 2️⃣ Age Density Plot (KDE)
- Smooth curve showing age concentration
- Highlights dominant age groups

### 3️⃣ Age Box Plot
- Reveals age spread and outliers
- Median age lies in the **early 30s**

### 4️⃣ Passenger Count by Gender
- Comparison of male vs female passengers
- **Male passengers are the majority**

### 5️⃣ Passenger Distribution by Class
- Majority traveled in **3rd class**
- Fewer passengers in **1st class**

### 6️⃣ Age vs Fare Scatter Plot
- Shows relationship between passenger age and fare
- Higher fares are generally associated with older passengers
- Indicates class-based pricing trends

---

## 🛠️ Technologies Used
- **Python 3.7+**
- **Pandas** – data manipulation
- **Matplotlib** – data visualization
- **Seaborn** – statistical plotting
- **Jupyter Notebook**

---

## 🚀 How to Replicate

### 🔧 Prerequisites
Install required libraries:

```bash
pip install pandas==2.0.3 numpy==1.24.3 matplotlib==3.7.2 seaborn==0.12.2 jupyter==1.0.0
