# 📊 Student Performance Dashboard Project (Excel)

## 📌 Overview

This project demonstrates how to build a **Student Performance Dashboard using Microsoft Excel**.

It is designed for beginners to understand how to:

* Work with structured datasets
* Perform data analysis
* Create visual dashboards
* Extract meaningful insights from data

---

## 🎯 Objective

To analyze student performance using Excel and create a dashboard that provides clear insights into:

* Student scores
* Performance levels
* Branch-wise analysis
* Subject-wise trends

---

## 📁 Dataset Structure

| Column     | Description                      |
| ---------- | -------------------------------- |
| Student_ID | Unique student identifier        |
| Name       | Student name                     |
| Branch     | Department (CSE, ECE, EEE, etc.) |
| Subject    | Subject name                     |
| Marks      | Score obtained                   |
| Attendance | Attendance percentage            |

### Example

| Student_ID | Name | Branch | Subject | Marks | Attendance |
| ---------- | ---- | ------ | ------- | ----- | ---------- |
| 101        | Ravi | CSE    | Math    | 85    | 90         |
| 102        | Anu  | ECE    | Physics | 78    | 85         |

---

## ⚙️ Step-by-Step Implementation

### 🔹 Step 1: Data Understanding

* Each row represents one student record
* Columns define different attributes

📌 Ask:

* Who are the top performers?
* What is the average score?
* Does attendance affect marks?

---

### 🔹 Step 2: Data Cleaning

Clean the dataset using:

```excel
=TRIM(A2)
=PROPER(A2)
```

Tasks:

* Remove extra spaces
* Standardize text format
* Check for missing values

---

### 🔹 Step 3: Add Calculated Columns

#### ✅ Result (Pass/Fail)

```excel
=IF(E2>=40,"Pass","Fail")
```

#### ✅ Performance Level

```excel
=IF(E2>=75,"Excellent",IF(E2>=50,"Average","Poor"))
```

---

### 🔹 Step 4: Basic Analysis

```excel
Total Students:
=COUNT(A2:A50)

Average Marks:
=AVERAGE(E2:E50)

Highest Marks:
=MAX(E2:E50)

Lowest Marks:
=MIN(E2:E50)
```

---

### 🔹 Step 5: Pivot Tables

Create Pivot Tables:

#### 📊 Performance by Branch

* Rows → Branch
* Values → Average of Marks

#### 📊 Subject-wise Analysis

* Rows → Subject
* Values → Average Marks

#### 📊 Pass/Fail Count

* Rows → Result
* Values → Count

---

### 🔹 Step 6: Create Charts

* Bar Chart → Marks by Branch
* Pie Chart → Pass vs Fail
* Column Chart → Subject Performance

---

### 🔹 Step 7: Dashboard Creation

Create a new sheet → **Dashboard**

Add:

* Total Students
* Average Marks
* Top Student
* Charts

Design Tips:

* Use consistent color theme (Blue/Green)
* Align elements properly
* Add clear titles

---

### 🔹 Step 8: Insights

Analyze and answer:

* Which branch performs best?
* Which subject is most difficult?
* Is there a relationship between attendance and marks?

---

## 📈 Final Output

After completing this project, you will be able to:

* Analyze structured datasets
* Apply Excel formulas effectively
* Create Pivot Tables
* Build a professional dashboard
* Generate meaningful insights

---

## 💡 Key Learning

> Data → Cleaning → Analysis → Visualization → Insight

---

## 🚀 Conclusion

This project is a beginner-friendly introduction to Data Analytics using Excel.

It focuses on practical learning and helps develop analytical thinking.

> “You don’t just learn Excel…
> you learn how to think with data.”

---

## Author: <A.Anand Kumar> 
From cells to insights ✨ | Guided as part of a Data Analytics learning journey.
LinkedIn: www.linkedin.com/in/anand-kumar-anamaina-50041a290


<img width="935" height="725" alt="Dashboard" src="https://github.com/user-attachments/assets/04bb2be5-0c94-4448-a467-52b6c215b5f5" />

<img width="1069" height="663" alt="PIVOT ANALYSIS" src="https://github.com/user-attachments/assets/36634af6-d1b2-4d59-ae02-547417f4675c" />
