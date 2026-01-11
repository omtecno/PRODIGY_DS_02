# PRODIGY_DS_02
Comprehensive exploratory data analysis of the historic Titanic dataset to uncover patterns and factors affecting passenger survival during the tragic 1912 disaster

# Titanic Test Dataset – Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project performs **Exploratory Data Analysis (EDA)** on the **Titanic test dataset** using Python.  
The goal is to **clean the data**, **handle missing values**, and **visualize important patterns** related to passenger demographics and ticket fares.

> ⚠️ Note: This dataset does **not** contain survival information (`Survived` column), as it is the Titanic **test dataset**.

---

## 📂 Dataset Information
- **Source:** Titanic Test Dataset
- **Rows:** 418 passengers
- **Columns:** 11 features

### Features:
| Column | Description |
|------|-------------|
| PassengerId | Unique passenger ID |
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
- Checked and confirmed **no duplicate records**
- Ensured dataset contains **no null values**

✔ Dataset is now clean and analysis-ready.

---

## 📊 Exploratory Data Analysis

### 1️⃣ Age Distribution (Histogram)
- Shows the overall distribution of passenger ages
- Most passengers fall between **20–40 years**

### 2️⃣ Age Density Plot (KDE)
- Smooth visualization of age concentration
- Helps understand passenger age trends

### 3️⃣ Age Box Plot
- Identifies **outliers** and age spread
- Median age around early 30s

### 4️⃣ Passenger Count by Gender
- Visual comparison of **male vs female** passengers
- Male passengers are the majority

### 5️⃣ Passenger Distribution by Class
- Most passengers belong to **3rd class**
- Fewer passengers in **1st class**

### 6️⃣ Age vs Fare Scatter Plot
- Shows relationship between passenger age and ticket fare
- Higher fares are mostly associated with **older passengers**
- Indicates class-based pricing trends

---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – data manipulation
- **Matplotlib** – plotting
- **Seaborn** – statistical visualizations

---

## 📁 Project Structure
