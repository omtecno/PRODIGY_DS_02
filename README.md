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
- <img width="772" height="597" alt="Age Distribution of Passengers" src="https://github.com/user-attachments/assets/edaf04bd-b25d-4038-a7e5-7daf67e80036" />


### 2️⃣ Age Density Plot (KDE)
- Smooth visualization of age concentration
- Helps understand passenger age trends
- <img width="787" height="597" alt="Age Density Distribution" src="https://github.com/user-attachments/assets/f2c6b05a-784c-433a-a055-d0f899a7955f" />


### 3️⃣ Age Box Plot
- Identifies **outliers** and age spread
- Median age around early 30s
- <img width="693" height="592" alt="Age Distribution (Box Plot)" src="https://github.com/user-attachments/assets/e62a53a2-c973-41fc-a7ca-7706026a40dc" />


### 4️⃣ Passenger Count by Gender
- Visual comparison of **male vs female** passengers
- Male passengers are the majority
- <img width="812" height="603" alt="Passenger Count by Gender" src="https://github.com/user-attachments/assets/09eccea3-d1b9-4fc2-b019-0586ffa0250c" />


### 5️⃣ Passenger Distribution by Class
- Most passengers belong to **3rd class**
- Fewer passengers in **1st class**
- <img width="821" height="593" alt="Passenger Distribution by Class" src="https://github.com/user-attachments/assets/1a346feb-6f23-47d5-9bdc-3ad10e424b18" />


### 6️⃣ Age vs Fare Scatter Plot
- Shows relationship between passenger age and ticket fare
- Higher fares are mostly associated with **older passengers**
- Indicates class-based pricing trends
- <img width="816" height="605" alt="Scatter plot of Age and Fare" src="https://github.com/user-attachments/assets/a0699731-aeb0-4fc4-beaa-2842451317f5" />


---

## 🛠️ Technologies Used
- **Python**
- **Pandas** – data manipulation
- **Matplotlib** – plotting
- **Seaborn** – statistical visualizations


🚀 ##How to Replicate
✅ #Prerequisites

Before running this project, ensure the following requirements are met:

🔹 #Software Requirements
pip install pandas==2.0.3 numpy==1.24.3 matplotlib==3.7.2 seaborn==0.12.2 jupyter==1.0.0

Python 3.7 or higher

https://github.com/omtecno/PRODIGY_DS_02/tree/main

Any Python IDE or environment such as:

Jupyter Notebook

Open notebook
Untitled5.ipynb


