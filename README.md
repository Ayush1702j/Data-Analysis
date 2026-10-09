# 📊 Data Analysis

Welcome to my **Data Analysis Repository**! 🚀

This repository represents my journey of learning and practicing **Data
Analysis using Python, NumPy, Pandas, SQL, Statistics, and Data
Visualization**.

It contains programming practice, data-cleaning exercises, Exploratory
Data Analysis (EDA), statistical analysis, visualization techniques,
datasets, SQL queries, and practical data analysis projects.

The main goal of this repository is to learn how to transform **raw data
into meaningful insights** that can support better decision-making.

------------------------------------------------------------------------

## 📌 About Data Analysis

**Data Analysis** is the process of collecting, cleaning, transforming,
exploring, analyzing, and interpreting data to discover useful
information, patterns, trends, and relationships.

In simple words:

> **Data Analysis converts raw data into meaningful insights that help
> us understand problems and make better decisions.**

For example, a company may analyze customer and sales data to find:

-   Which product has the highest sales?
-   Which city generates the most revenue?
-   Which month has the highest sales?
-   Who are the most valuable customers?
-   Are there unusual values or outliers?
-   Which factors affect sales?
-   What trends can be observed?
-   What may happen in the future?

------------------------------------------------------------------------

# 🎯 Objectives

The main objectives of this repository are:

-   Learn the fundamentals of Data Analysis.
-   Strengthen Python programming skills.
-   Learn NumPy for numerical computing.
-   Learn Pandas for data manipulation.
-   Understand data cleaning and preprocessing.
-   Perform Exploratory Data Analysis (EDA).
-   Understand important statistical concepts.
-   Create meaningful data visualizations.
-   Identify patterns and trends in datasets.
-   Analyze relationships between variables.
-   Detect outliers and anomalies.
-   Practice SQL for data analysis.
-   Work with real-world datasets.
-   Build practical Data Analysis projects.
-   Develop analytical and problem-solving skills.
-   Build a strong foundation for Data Science and Machine Learning.

------------------------------------------------------------------------

# 🔄 Data Analysis Workflow

``` text
                    Raw Data
                       ↓
                Data Collection
                       ↓
              Data Understanding
                       ↓
                Data Cleaning
                       ↓
             Data Preprocessing
                       ↓
         Exploratory Data Analysis
                       ↓
             Statistical Analysis
                       ↓
              Data Visualization
                       ↓
              Pattern Detection
                       ↓
              Insight Generation
                       ↓
             Decision Making
```

------------------------------------------------------------------------

# 📚 Topics Covered

## 1. 🐍 Python for Data Analysis

Python is one of the most widely used programming languages for Data
Analysis because of its simplicity and powerful libraries.

### Topics Covered

-   Variables
-   Data Types
-   Operators
-   Conditional Statements
-   Loops
-   Functions
-   Lists
-   Tuples
-   Sets
-   Dictionaries
-   Strings
-   File Handling
-   Exception Handling
-   Modules
-   Basic Object-Oriented Programming

### Example

``` python
numbers = [10, 20, 30, 40, 50]

total = sum(numbers)
average = total / len(numbers)

print("Total:", total)
print("Average:", average)
```

------------------------------------------------------------------------

# 2. 🔢 NumPy

**NumPy (Numerical Python)** is a Python library used for numerical
computing and scientific operations.

### Topics Covered

-   NumPy Arrays
-   Array Creation
-   Array Indexing
-   Array Slicing
-   Array Dimensions
-   Reshaping
-   Mathematical Operations
-   Statistical Functions
-   Aggregation
-   Broadcasting
-   Random Number Generation
-   Matrix Operations

### Example

``` python
import numpy as np

data = np.array([10, 20, 30, 40, 50])

print("Mean:", np.mean(data))
print("Maximum:", np.max(data))
print("Minimum:", np.min(data))
print("Sum:", np.sum(data))
```

------------------------------------------------------------------------

# 3. 🐼 Pandas

**Pandas** is one of the most important Python libraries for Data
Analysis.

It provides two major data structures:

-   Series
-   DataFrame

### Topics Covered

-   Creating Series
-   Creating DataFrames
-   Reading CSV files
-   Reading Excel files
-   Inspecting datasets
-   Selecting rows and columns
-   Filtering data
-   Sorting data
-   Adding columns
-   Removing columns
-   Renaming columns
-   Handling missing values
-   Removing duplicates
-   GroupBy
-   Aggregation
-   Merge
-   Join
-   Concatenation
-   Pivot Tables
-   Data Type Conversion

### Example

``` python
import pandas as pd

df = pd.read_csv("data.csv")

print(df.head())
print(df.info())
print(df.describe())
```

------------------------------------------------------------------------

# 4. 🧹 Data Cleaning

Real-world datasets are often incomplete or inconsistent.

A dataset may contain:

-   Missing values
-   Duplicate records
-   Incorrect data types
-   Invalid values
-   Outliers
-   Inconsistent formatting
-   Incorrect spellings
-   Unnecessary columns

### Check Missing Values

``` python
df.isnull().sum()
```

### Remove Missing Values

``` python
df.dropna()
```

### Fill Missing Values

``` python
df.fillna(0)
```

### Remove Duplicate Records

``` python
df.drop_duplicates()
```

### Convert Data Types

``` python
df["Age"] = df["Age"].astype(int)
```

------------------------------------------------------------------------

# 5. 🔎 Exploratory Data Analysis (EDA)

**Exploratory Data Analysis (EDA)** is the process of investigating a
dataset to understand its structure, characteristics, patterns,
relationships, and possible problems.

EDA helps answer questions such as:

-   How many rows are present?
-   How many columns are present?
-   What type of data is available?
-   Are there missing values?
-   Are there duplicate records?
-   What are the minimum and maximum values?
-   How is the data distributed?
-   Are there outliers?
-   Are variables correlated?
-   Which categories occur most frequently?

### Common Pandas Commands

``` python
df.head()
df.tail()
df.shape
df.columns
df.info()
df.describe()
df.isnull().sum()
df.duplicated().sum()
```

------------------------------------------------------------------------

# 6. 📊 Data Visualization

Data Visualization represents information using charts and graphs.

Visualization makes it easier to understand:

-   Trends
-   Patterns
-   Comparisons
-   Relationships
-   Distributions
-   Outliers
-   Category-wise performance

### Common Visualizations

  Visualization   Purpose
  --------------- -------------------------
  Line Chart      Show trends over time
  Bar Chart       Compare categories
  Pie Chart       Show proportions
  Histogram       Show data distribution
  Scatter Plot    Show relationships
  Box Plot        Detect outliers
  Heatmap         Show correlation
  Area Chart      Show changes over time
  Count Plot      Show category frequency

## 📈 Line Chart

``` python
import matplotlib.pyplot as plt

plt.plot(months, sales)

plt.title("Monthly Sales")
plt.xlabel("Month")
plt.ylabel("Sales")

plt.show()
```

## 📊 Bar Chart

``` python
plt.bar(products, sales)

plt.title("Product Sales")
plt.xlabel("Product")
plt.ylabel("Sales")

plt.show()
```

## 🥧 Pie Chart

``` python
plt.pie(
    sales,
    labels=products,
    autopct="%1.1f%%"
)

plt.title("Sales Distribution")

plt.show()
```

## 🔵 Scatter Plot

``` python
plt.scatter(age, salary)

plt.xlabel("Age")
plt.ylabel("Salary")

plt.title("Age vs Salary")

plt.show()
```

## 📦 Box Plot

``` python
plt.boxplot(salary)

plt.title("Salary Distribution")

plt.show()
```

------------------------------------------------------------------------

# 7. 📐 Statistical Analysis

Important statistical concepts include:

-   Mean
-   Median
-   Mode
-   Minimum
-   Maximum
-   Range
-   Variance
-   Standard Deviation
-   Percentiles
-   Quartiles
-   Correlation
-   Covariance

### Mean

``` python
df["Salary"].mean()
```

### Median

``` python
df["Salary"].median()
```

### Mode

``` python
df["Salary"].mode()
```

### Standard Deviation

``` python
df["Salary"].std()
```

------------------------------------------------------------------------

# 8. 🔗 Correlation Analysis

Correlation helps identify the relationship between two variables.

``` text
-1 ---------------- 0 ---------------- +1

Strong Negative    No/Weak            Strong Positive
Correlation        Correlation         Correlation
```

Example:

If study hours increase and marks also increase, there may be a
**positive correlation** between study hours and marks.

``` python
df.corr(numeric_only=True)
```

> Correlation does not necessarily mean that one variable causes the
> other.

------------------------------------------------------------------------

# 9. 🚨 Outlier Detection

An **outlier** is a value that is significantly different from the other
observations.

Example:

``` text
10
12
11
13
15
100
```

Here, `100` may be considered an outlier depending on the dataset and
analysis.

### Common Methods

-   Box Plot
-   IQR Method
-   Z-Score
-   Statistical Analysis

### IQR Method

``` python
Q1 = df["Salary"].quantile(0.25)
Q3 = df["Salary"].quantile(0.75)

IQR = Q3 - Q1

lower = Q1 - 1.5 * IQR
upper = Q3 + 1.5 * IQR

outliers = df[
    (df["Salary"] < lower) |
    (df["Salary"] > upper)
]
```

------------------------------------------------------------------------

# 10. 📊 GroupBy and Aggregation

The `groupby()` function allows data to be analyzed based on categories.

``` python
df.groupby("Department")["Marks"].mean()
```

Common aggregation functions:

``` text
mean()
sum()
count()
min()
max()
median()
```

Example:

``` python
df.groupby("Department")["Salary"].sum()
```

------------------------------------------------------------------------

# 11. 🔄 Data Transformation

Common data transformation operations include:

-   Renaming columns
-   Changing data types
-   Creating new columns
-   Applying functions
-   Encoding categories
-   Scaling numerical values
-   Extracting date information
-   Combining columns

Example:

``` python
df["Total"] = df["Price"] * df["Quantity"]
```

------------------------------------------------------------------------

# 12. 🗃️ SQL for Data Analysis

SQL is used to retrieve and analyze data stored in relational databases.

### Topics Covered

-   SELECT
-   WHERE
-   ORDER BY
-   GROUP BY
-   HAVING
-   DISTINCT
-   Aggregate Functions
-   JOIN
-   Subqueries
-   CASE
-   INSERT
-   UPDATE
-   DELETE

### Example

``` sql
SELECT department, AVG(salary)
FROM employees
GROUP BY department;
```

------------------------------------------------------------------------

# 📋 Types of Data Analysis

There are four major types of Data Analysis.

## 1. Descriptive Analysis

Answers:

> **What happened?**

Example:

``` text
Total Sales = ₹10,00,000
Average Sales = ₹25,000
```

It summarizes historical data.

## 2. Diagnostic Analysis

Answers:

> **Why did it happen?**

``` text
Sales Decreased
       ↓
Customer Orders Decreased
       ↓
Product Prices Increased
       ↓
Customer Demand Decreased
```

It focuses on identifying possible reasons behind an event.

## 3. Predictive Analysis

Answers:

> **What is likely to happen?**

``` text
Historical Data
       ↓
Analysis / Model
       ↓
Future Prediction
```

## 4. Prescriptive Analysis

Answers:

> **What should we do?**

``` text
Sales are decreasing
       ↓
Analyze Customer Behavior
       ↓
Identify Problem
       ↓
Recommend Action
       ↓
Improve Sales
```

------------------------------------------------------------------------

# 🛠️ Tools & Technologies

  Technology         Purpose
  ------------------ -------------------------------
  Python             Programming and Data Analysis
  NumPy              Numerical Computing
  Pandas             Data Manipulation
  Matplotlib         Data Visualization
  Seaborn            Statistical Visualization
  Jupyter Notebook   Interactive Analysis
  Google Colab       Cloud-Based Analysis
  Excel              Spreadsheet Analysis
  SQL                Database Analysis
  Power BI           Business Intelligence
  Tableau            Data Visualization
  Git                Version Control
  GitHub             Repository Management

------------------------------------------------------------------------

# 📦 Python Libraries

``` python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

Additional libraries may be used depending on the project.

------------------------------------------------------------------------

# 📁 Repository Structure

``` text
Data-Analysis/
│
├── README.md
│
├── Python/
│   ├── Basics/
│   ├── Functions/
│   ├── Data_Structures/
│   └── File_Handling/
│
├── NumPy/
│   ├── Arrays/
│   ├── Operations/
│   ├── Mathematics/
│   └── Practice/
│
├── Pandas/
│   ├── Series/
│   ├── DataFrame/
│   ├── Data_Cleaning/
│   ├── GroupBy/
│   └── Practice/
│
├── Statistics/
│   ├── Descriptive_Statistics/
│   ├── Correlation/
│   └── Probability/
│
├── EDA/
│   ├── Datasets/
│   ├── Notebooks/
│   └── Analysis/
│
├── Visualization/
│   ├── Matplotlib/
│   └── Seaborn/
│
├── SQL/
│   ├── Queries/
│   ├── Joins/
│   └── Practice/
│
├── Projects/
│   ├── Project-1/
│   ├── Project-2/
│   └── Project-3/
│
└── Datasets/
    ├── CSV/
    └── Excel/
```

> The folder structure can be updated as new topics and projects are
> added.

------------------------------------------------------------------------

# 💻 Example Data Analysis

Suppose we have a customer dataset:

``` text
Customer | Age | City   | Purchase
-----------------------------------
A        | 21  | Pune   | 500
B        | 25  | Mumbai | 900
C        | 20  | Pune   | 700
D        | 30  | Delhi  | 400
```

### Load Dataset

``` python
import pandas as pd

df = pd.read_csv("customers.csv")
```

### View Dataset

``` python
print(df.head())
```

### Check Dataset Information

``` python
print(df.info())
```

### Statistical Summary

``` python
print(df.describe())
```

### Calculate Average Purchase

``` python
print(df["Purchase"].mean())
```

### Analyze Purchases by City

``` python
print(df.groupby("City")["Purchase"].mean())
```

### Visualize Results

``` python
import matplotlib.pyplot as plt

df.groupby("City")["Purchase"].mean().plot(kind="bar")

plt.title("Average Purchase by City")
plt.xlabel("City")
plt.ylabel("Average Purchase")

plt.show()
```

------------------------------------------------------------------------

# 📊 Data Analysis Project Workflow

``` text
Problem Definition
       ↓
Data Collection
       ↓
Data Understanding
       ↓
Data Cleaning
       ↓
Data Preprocessing
       ↓
EDA
       ↓
Statistical Analysis
       ↓
Visualization
       ↓
Insight Generation
       ↓
Conclusion
```

The objective is not only to create graphs but also to explain **what
the data is telling us**.

------------------------------------------------------------------------

# 🧠 Skills Developed

Through this repository, I am developing skills in:

-   Python Programming
-   NumPy
-   Pandas
-   Data Cleaning
-   Data Preprocessing
-   Exploratory Data Analysis
-   Statistical Analysis
-   Data Visualization
-   Data Interpretation
-   SQL
-   Excel
-   Power BI
-   Tableau
-   Problem Solving
-   Analytical Thinking
-   Data Storytelling
-   Git
-   GitHub

------------------------------------------------------------------------

# 📈 Learning Roadmap

``` text
Python
   ↓
NumPy
   ↓
Pandas
   ↓
Data Cleaning
   ↓
Statistics
   ↓
EDA
   ↓
Matplotlib / Seaborn
   ↓
SQL
   ↓
Excel
   ↓
Power BI / Tableau
   ↓
Real-World Projects
   ↓
Advanced Data Analysis
   ↓
Data Science
   ↓
Machine Learning
```

------------------------------------------------------------------------

# 🚀 Practical Projects

This repository will contain practical exercises and real-world data
analysis projects covering areas such as:

### 📊 Exploratory Data Analysis

Analyzing datasets to identify patterns, trends, relationships, and
anomalies.

### 📈 Sales Analysis

Analyzing sales data to understand:

-   Revenue
-   Product performance
-   Customer behavior
-   Monthly trends
-   Regional performance

### 👥 Customer Analysis

Analyzing customer information to understand:

-   Customer segments
-   Purchasing behavior
-   Customer value
-   Spending patterns

### 📉 Statistical Analysis

Applying statistical methods to understand distributions, relationships,
and trends.

### 📊 Business Intelligence

Creating dashboards and reports using:

-   Excel
-   Power BI
-   Tableau

------------------------------------------------------------------------

# 🔮 Future Improvements

I will continue improving this repository by adding:

-   More Python practice programs
-   Advanced NumPy operations
-   Advanced Pandas operations
-   More real-world datasets
-   Advanced EDA projects
-   Statistical analysis projects
-   SQL projects
-   Excel dashboards
-   Power BI dashboards
-   Tableau dashboards
-   Data storytelling projects
-   End-to-end Data Analysis projects
-   Data Science projects
-   Machine Learning projects

------------------------------------------------------------------------

# 🎯 Goal

The long-term goal of this repository is to build strong practical
knowledge in:

**Data Analysis → Data Science → Machine Learning**

The main focus is not only on writing code but also on understanding the
complete analytical process:

``` text
What happened?
      ↓
Why did it happen?
      ↓
What patterns exist?
      ↓
What relationships exist?
      ↓
What may happen next?
      ↓
What should we do?
```

------------------------------------------------------------------------

# 📚 What I Am Learning

My current focus is on building a strong foundation in:

``` text
Python
   +
NumPy
   +
Pandas
   +
Statistics
   +
EDA
   +
Data Visualization
   +
SQL
   +
Excel
   +
Power BI
   +
Tableau
```

These skills provide a foundation for further learning in **Data
Science, Artificial Intelligence, and Machine Learning**.

------------------------------------------------------------------------

# ⭐ Conclusion

Data Analysis is an important skill for converting raw data into useful
information and actionable insights.

This repository documents my learning journey through:

**Python → NumPy → Pandas → Data Cleaning → EDA → Statistics →
Visualization → SQL → BI → Real-World Projects**

I will continue updating this repository as I learn new concepts, solve
problems, analyze datasets, and build practical projects.

------------------------------------------------------------------------

# 👨‍💻 Author

## Ayush Jugseniye

**Computer Engineering Student**

### Interests

-   📊 Data Analysis
-   📈 Data Science
-   🤖 Artificial Intelligence
-   🧠 Machine Learning
-   🐍 Python
-   🗄️ SQL
-   📊 Business Intelligence
-   📉 Data Visualization

------------------------------------------------------------------------

# ⭐ Support

If you find this repository useful, please consider giving it a ⭐ on
GitHub.

Thank you for visiting my **Data Analysis Repository!** 🚀
