# 💼 Samuel Head's Data Portfolio

Welcome to my data portfolio! This repository showcases a collection of projects that demonstrate my skills in SQL, data analysis, and other related fields. Each project includes detailed documentation and the corresponding code or queries, designed to solve real-world problems or provide valuable insights.

## 📌 Featured Projects

### 1. 🛒 Superstore Project Database

**Objective:** Analyzed a fictional superstore dataset to uncover insights about inventory, pricing, and customer preferences.

**Key Skills:** SQL, Data Analysis

**Highlights:**
- Created a relational database from raw data.
- Performed complex queries to identify high-demand products and optimize inventory management.
- Generated reports on pricing trends and customer ratings.

[Explore the Project](https://github.com/ImEyePatch/SQL/blob/main/Superstore%20Project%20Database)

### 2. 💼 Project 2: SQL Fortune 500 Companies Analysis
Dataset: The dataset represents a list of Fortune 500 companies with attributes such as company name, industry, revenue, employee count, healthcare benefits, paid time off (PTO) days, maternity leave weeks, and average employee tenure.

Key SQL Queries:

How does employee tenure differ between industries with and without healthcare benefits?

SELECT ROUND(AVG(avg_employee_tenure), 1) AS "Average Tenure",
CASE WHEN healthcare_benefits = 1 THEN "HAS BENEFITS" 
     WHEN healthcare_benefits = 0 THEN "NO BENEFITS"
END AS "Healthcare"
FROM fortune_companies
GROUP BY healthcare_benefits;


[Explore the Project](./Project_2_Name/README.md)

### 3. 📈 Project 3 Name

**Objective:** Brief description of the project.

**Key Skills:** R, Statistical Analysis, Data Cleaning

**Highlights:**
- Key achievement or result 1.
- Key achievement or result 2.

[Explore the Project](./Project_3_Name/README.md)

## 🚀 Getting Started

Each project folder contains its own README file with detailed instructions on how to set up and run the code. You can navigate to the individual project folders to dive deeper into the specific analyses and results.

## 🛠️ Tools & Technologies

- **SQL** for database management and queries.
- **Python** for data manipulation and machine learning.
- **R** for statistical analysis and visualization.
- **Tableau** for creating interactive dashboards.

## 🧠 About Me

I'm Samuel Head, a data enthusiast with a passion for turning raw data into actionable insights. My background includes experience in technical support, sales, and solar energy, with a strong focus on data-driven decision-making.

## 📫 Contact

Feel free to reach out to me via [LinkedIn](https://www.linkedin.com/) or [Email](mailto:your.email@example.com).

---

This README gives an overview of your portfolio, highlights key projects, and provides easy navigation for potential employers or collaborators.
