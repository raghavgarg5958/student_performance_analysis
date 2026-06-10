# 📊 Student Performance Analysis using Python

## 📌 Overview

This project analyzes student academic performance using Python and data analysis techniques. The objective is to explore factors affecting student grades, identify patterns in academic performance, and present insights through statistical analysis and visualizations.

The analysis is based on the **Student Mathematics Performance Dataset** and was completed as part of a **Data Analysis with Python Internship** task.

---

## 🎯 Objectives

* Explore and understand the dataset.
* Perform data cleaning and preprocessing.
* Analyze student performance using statistical methods.
* Study the relationship between study time and final grades.
* Compare academic performance across genders.
* Evaluate grade progression throughout the academic year.
* Create meaningful visualizations to communicate findings.

---

## 🛠️ Tech Stack

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Jupyter Notebook / Google Colab**

---

## 📂 Dataset Information

The dataset contains demographic, social, and academic information about students enrolled in Mathematics courses.

### Key Features

| Feature   | Description         |
| --------- | ------------------- |
| sex       | Student Gender      |
| age       | Student Age         |
| studytime | Weekly Study Time   |
| absences  | Number of Absences  |
| G1        | First Period Grade  |
| G2        | Second Period Grade |
| G3        | Final Grade         |

---

## 🔍 Analysis Performed

### Data Exploration

* Examined dataset structure and dimensions.
* Inspected data types and feature information.
* Checked for missing values.
* Removed duplicate records.

### Statistical Analysis

* Calculated average final grade (G3).
* Counted students scoring above 15.
* Measured correlation between study time and final grades.
* Compared average grades by gender.
* Analyzed performance progression across G1, G2, and G3.

---

## 📈 Data Visualization

### 1. Distribution of Final Grades

**Histogram**

* Visualizes the distribution of students' final grades (G3).

### 2. Study Time vs Final Grade

**Scatter Plot**

* Shows the relationship between study time and academic performance.

### 3. Gender-wise Performance

**Bar Chart**

* Compares average final grades between male and female students.

### 4. Academic Progression

**G1, G2, and G3 Comparison**

* Examines how student performance changes across different assessment periods.

### 5. Average Grade Comparison

**Bar Chart**

* Compares average values of G1, G2, and G3 to identify overall performance trends.

---

## 📊 Key Findings

### Average Final Grade (G3)

**10.42**

### Students Scoring Above 15

**40 Students**

### Correlation Between Study Time and Final Grade

**0.098**

This indicates a very weak positive correlation between study time and final academic performance.

### Average Grade by Gender

| Gender | Average Grade |
| ------ | ------------- |
| Male   | 10.91         |
| Female | 9.97          |

Male students achieved slightly higher average final grades in this dataset.

---

## 💡 Insights

* Most students scored within the middle grade range.
* Only a limited number of students achieved scores above 15.
* Study time alone does not strongly predict academic success.
* Student performance remained relatively consistent across assessment periods.
* Gender-based differences exist but are not substantial.

---

## 📁 Project Structure

```text
Student-Performance-Analysis/
│
├── student-mat.csv
├── Task1_Student_Performance_Analysis.ipynb
├── README.md
│
└── images/
    ├── grade_distribution.png
    ├── studytime_vs_grade.png
    ├── gender_comparison.png
    └── grade_progression.png
```

---

## 🎓 Internship Task

This project was completed as part of the **Data Analysis with Python Internship – Task 1**.

### Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Statistical Analysis
* Data Visualization
* Insight Generation
* Python Programming

---

## ⭐ Future Enhancements

* Develop predictive models for student performance.
* Apply machine learning techniques for grade prediction.
* Create interactive dashboards using Plotly or Power BI.
* Perform advanced feature analysis and model evaluation.

---

## 👨‍💻 Author

**Raghav Garg**

Computer Science Student | Data Analytics Enthusiast

If you found this project useful, consider giving it a ⭐ on GitHub.
