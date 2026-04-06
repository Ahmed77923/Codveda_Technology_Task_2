# 🚢 Titanic Dataset - Exploratory Data Analysis (EDA)

## 📌 Project Overview

This project is part of the **Codveda Data Analytics Internship – Task 2**.
The goal is to perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to uncover patterns, relationships, and key factors influencing passenger survival.

---

## 🎯 Objectives

* Understand the structure and distribution of the dataset
* Identify trends and patterns
* Analyze relationships between variables
* Extract meaningful insights to support decision-making

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## 📂 Dataset

* **Name:** Titanic Dataset
* **Description:** Contains information about passengers such as age, gender, class, fare, and survival status

---

## 🔍 Data Analysis Steps

### 1. Summary Statistics

Basic statistical measures were calculated:

* Mean, Median, Mode
* Standard Deviation

**Insight**

* The dataset shows variation in passenger age and ticket fares.
* Fare distribution has high variance, indicating inequality among passengers.

---

### 2. Age Distribution

A histogram was used to analyze the distribution of passenger ages.

**Insight**

* The majority of passengers were between **20 and 40 years old**
* The distribution is slightly **right-skewed**
* Fewer children and elderly passengers are present

---

### 3. Fare Distribution

A histogram and boxplot were used to analyze ticket fares.

**Insight**

* Fare distribution is **highly skewed to the right**
* Presence of significant **outliers** (very high fares)
* Indicates economic differences between passengers

---

### 4. Age vs Fare Relationship

A scatter plot was used to explore the relationship between age and fare.

**Insight**

* No strong correlation between **Age** and **Fare**
* Most passengers paid lower fares regardless of age

---

### 5. Correlation Analysis

A heatmap was used to visualize relationships between numerical features.

**Key Findings**

* **Pclass and Fare** are strongly negatively correlated
* Lower class number (1st class) corresponds to higher fares
* Family-related variables (**SibSp, Parch**) show moderate correlation

---

## 🧠 Survival Analysis (Key Section)

### Survival by Gender

**Insight**

* Female passengers had significantly higher survival rates than males
* Suggests priority evacuation policies (“women and children first”)

---

### Survival by Passenger Class

**Insight**

* First-class passengers had the highest survival rates
* Indicates socio-economic status played a major role in survival

---

### Survival by Fare

**Insight**

* Passengers who paid higher fares had better survival chances
* Strong connection between wealth and survival probability

---

## 📊 Key Insights Summary

* The dataset is dominated by young adult passengers
* Fare distribution reveals strong economic inequality
* Passenger class is a major factor influencing survival
* Gender has the strongest impact on survival outcomes
* No meaningful relationship between age and fare

---

## 🧾 Conclusion

This analysis highlights that survival on the Titanic was not random.
It was strongly influenced by **gender and socio-economic status**, with women and higher-class passengers having significantly better chances of survival.

EDA provides critical understanding before applying machine learning models and helps guide further analysis.

---

## 📁 Repository Structure

```
project/
│
├── data/
├── Task_2.ipynb
├── README.md
```

---

## 🚀 Future Work

* Feature Engineering (Age groups, family size)
* Predictive Modeling (Classification)
* Model evaluation and optimization

---

## 👤 Author

Ahmed77923
