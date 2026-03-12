# Codveda Data Analytics Internship – Task 2

## Exploratory Data Analysis (EDA)

This project is part of the **Codveda Data Analytics Internship**.  
The goal of this task is to perform **Exploratory Data Analysis (EDA)** to understand the dataset, identify patterns, trends, and relationships between variables.

Dataset used: **Titanic Dataset**

---

## Objectives

- Calculate summary statistics
- Visualize data distributions
- Identify patterns and trends
- Analyze relationships between numerical features

---

## Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Steps

 1. Summary Statistics
Basic statistics were calculated to understand the dataset, including:

- Mean
- Median
- Mode
- Standard Deviation

This helps to understand the overall distribution of numerical variables such as **Age** and **Fare**.

---

 2. Histogram – Age Distribution

A histogram was used to visualize how passenger ages are distributed.

**Insight**

Most passengers were between **20 and 35 years old**, with fewer children and elderly passengers.

---

 3. Boxplot – Age

A boxplot was used to detect **outliers** and understand the spread of age values.

**Insight**

Most ages fall between **22 and 35**, with a few outliers representing very young or elderly passengers.

---

 4. Scatter Plot – Age vs Fare

A scatter plot was created to explore the relationship between passenger **Age** and **Fare**.

**Insight**

Most passengers paid fares below **100**, and there is **no strong relationship between Age and Fare**.

---

5. Correlation Matrix

A correlation heatmap was used to analyze relationships between numerical variables.

**Key Findings**

- Passenger **class (Pclass)** has a strong relationship with **Fare**.
- **First-class passengers paid higher fares**.
- Passengers traveling with **siblings or spouses often traveled with family members**.

---

Conclusion

The exploratory analysis provided important insights into the dataset:

- Most passengers were young adults.
- First-class passengers paid higher ticket fares.
- Passenger age had little impact on ticket price.
- Family-related variables show moderate correlation.

EDA is an essential step before applying machine learning models or advanced analysis.

---
 Repository Structure
