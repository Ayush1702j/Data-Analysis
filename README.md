# 📊 Data Analysis

Welcome to my **Data Analysis** repository! 🚀

This repository contains my **Data Analysis learning journey, practice programs, datasets, Exploratory Data Analysis (EDA), data visualization, and real-world projects**.

The main purpose of this repository is to learn how to transform **raw data into meaningful insights** using Python and various data analysis tools.

---

## 📌 About Data Analysis

**Data Analysis** is the process of collecting, cleaning, transforming, exploring, and interpreting data to discover useful information, patterns, trends, and relationships.

In simple words:

> **Data Analysis converts raw data into meaningful insights that can help in decision-making.**

For example, a company may have thousands of customer records. Using Data Analysis, we can find:

* Which product is selling the most?
* Which city has the highest sales?
* Who are the most valuable customers?
* What are the monthly sales trends?
* Are there any unusual values?
* Which factors affect sales?

---

## 🎯 Objectives

The main objectives of this repository are:

* Learn the fundamentals of Data Analysis.
* Understand and work with real-world datasets.
* Learn data cleaning and preprocessing.
* Perform Exploratory Data Analysis (EDA).
* Understand basic statistical concepts.
* Create meaningful data visualizations.
* Identify patterns and trends.
* Analyze relationships between variables.
* Extract useful insights from datasets.
* Improve Python, NumPy, and Pandas skills.
* Practice SQL for data analysis.
* Build real-world Data Analysis projects.
* Develop a strong foundation for Data Science and Machine Learning.

---

# 🔄 Data Analysis Workflow

A typical Data Analysis workflow is:

```text
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
          Find Patterns
                  ↓
          Generate Insights
                  ↓
        Data-Driven Decisions
```

---

# 📚 Topics Covered

## 1. 🐍 Python for Data Analysis

Python is one of the most widely used programming languages for Data Analysis.

Topics include:

* Variables
* Data Types
* Operators
* Conditional Statements
* Loops
* Functions
* Lists
* Tuples
* Sets
* Dictionaries
* File Handling
* Exception Handling
* Modules

Example:

```python
numbers = [10, 20, 30, 40, 50]

total = sum(numbers)
average = total / len(numbers)

print("Total:", total)
print("Average:", average)
```

---

# 2. 🔢 NumPy

**NumPy (Numerical Python)** is a Python library used for numerical and scientific computing.

### Topics Covered

* NumPy Arrays
* Array Creation
* Array Indexing
* Array Slicing
* Array Dimensions
* Reshaping
* Mathematical Operations
* Statistical Functions
* Aggregation
* Broadcasting
* Random Number Generation

### Example

```python
import numpy as np

data = np.array([10, 20, 30, 40, 50])

print("Mean:", np.mean(data))
print("Maximum:", np.max(data))
print("Minimum:", np.min(data))
print("Sum:", np.sum(data))
```

---

# 3. 🐼 Pandas

**Pandas** is one of the most important Python libraries for Data Analysis.

It provides two important data structures:

* Series
* DataFrame

### Topics Covered

* Creating Series
* Creating DataFrames
* Reading CSV files
* Reading Excel files
* Inspecting datasets
* Selecting rows and columns
* Filtering data
* Sorting data
* Adding columns
* Removing columns
* Handling missing values
* Removing duplicate records
* GroupBy
* Aggregation
* Merge
* Join
* Concatenation
* Pivot Tables

### Example

```python
import pandas as pd

df = pd.read_csv("data.csv")

print(df.head())
print(df.info())
print(df.describe())
```

---

# 4. 🧹 Data Cleaning

Real-world data is usually not perfect.

A dataset can contain:

* Missing values
* Duplicate records
* Incorrect data types
* Invalid values
* Outliers
* Inconsistent formatting
* Incorrect spellings
* Unnecessary columns

Data Cleaning is performed before analysis to improve the quality of the data.

### Checking Missing Values

```python
df.isnull().sum()
```

### Removing Missing Values

```python
df.dropna()
```

### Filling Missing Values

```python
df.fillna(0)
```

### Removing Duplicate Records

```python
df.drop_duplicates()
```

---

# 5. 🔎 Exploratory Data Analysis (EDA)

**Exploratory Data Analysis (EDA)** is the process of investigating a dataset to understand its structure, patterns, relationships, and characteristics.

EDA helps answer questions such as:

* How many rows are present?
* How many columns are present?
* What type of data is available?
* Are there missing values?
* Are there duplicate records?
* What are the minimum and maximum values?
* What is the distribution of the data?
* Are there outliers?
* Are variables correlated?

### Common Pandas Commands

```python
df.head()
```

Displays the first few records.

```python
df.tail()
```

Displays the last few records.

```python
df.shape
```

Returns the number of rows and columns.

```python
df.columns
```

Displays column names.

```python
df.info()
```

Provides information about the dataset.

```python
df.describe()
```

Provides statistical summary.

```python
df.isnull().sum()
```

Checks missing values.

---

# 6. 📊 Data Visualization

Data Visualization represents data using graphs and charts.

Visualization makes it easier to identify:

* Trends
* Patterns
* Relationships
* Comparisons
* Distributions
* Outliers

### Common Charts

| Visualization | Purpose               |
| ------------- | --------------------- |
| Line Chart    | Show trends over time |
| Bar Chart     | Compare categories    |
| Pie Chart     | Show proportions      |
| Histogram     | Show distribution     |
| Scatter Plot  | Show relationship     |
| Box Plot      | Detect outliers       |
| Heatmap       | Show correlation      |

---

## 📈 Line Chart

A line chart is commonly used to show changes or trends over time.

```python
import matplotlib.pyplot as plt

plt.plot(months, sales)

plt.title("Monthly Sales")
plt.xlabel("Month")
plt.ylabel("Sales")

plt.show()
```

---

## 📊 Bar Chart

Bar charts are useful for comparing different categories.

```python
plt.bar(products, sales)

plt.title("Product Sales")
plt.xlabel("Product")
plt.ylabel("Sales")

plt.show()
```

---

## 🥧 Pie Chart

Pie charts show how a total is divided into different categories.

```python
plt.pie(sales, labels=products, autopct="%1.1f%%")

plt.title("Sales Distribution")

plt.show()
```

---

## 🔵 Scatter Plot

Scatter plots are used to understand the relationship between two numerical variables.

```python
plt.scatter(age, salary)

plt.xlabel("Age")
plt.ylabel("Salary")

plt.title("Age vs Salary")

plt.show()
```

---

## 📦 Box Plot

Box plots can be used to understand data distribution and identify possible outliers.

```python
plt.boxplot(salary)

plt.title("Salary Distribution")

plt.show()
```

---

# 7. 📐 Statistical Analysis

Statistics is an important part of Data Analysis.

Important statistical concepts include:

* Mean
* Median
* Mode
* Minimum
* Maximum
* Range
* Variance
* Standard Deviation
* Percentiles
* Quartiles
* Correlation

### Mean

The mean represents the average value.

```python
df["Salary"].mean()
```

### Median

The median represents the middle value when data is arranged in order.

```python
df["Salary"].median()
```

### Standard Deviation

Standard deviation measures how spread out the values are.

```python
df["Salary"].std()
```

---

# 8. 🔗 Correlation Analysis

Correlation helps identify the relationship between two variables.

The correlation value generally ranges from:

```text
-1 ---------------- 0 ---------------- +1
Strong Negative    No Relationship    Strong Positive
```

Example:

```python
df.corr(numeric_only=True)
```

### Example

If study hours increase and marks also increase, there may be a **positive correlation** between study hours and marks.

---

# 9. 🚨 Outlier Detection

An **outlier** is a value that is significantly different from the other observations.

Example:

```text
10
12
11
13
15
100
```

Here, `100` may be considered an outlier.

Common techniques for detecting outliers include:

* Box Plot
* IQR Method
* Z-Score
* Statistical Analysis

---

# 10. 📊 GroupBy and Aggregation

Grouping allows us to analyze data based on categories.

For example:

```python
df.groupby("Department")["Marks"].mean()
```

This can answer:

> What is the average marks for each department?

Common aggregation functions:

```python
mean()
sum()
count()
min()
max()
median()
```

Example:

```python
df.groupby("Department")["Salary"].sum()
```

---

# 📋 Types of Data Analysis

There are four major types of Data Analysis.

## 1. Descriptive Analysis

Answers:

> **What happened?**

Example:

```text
Total Sales = ₹10,00,000
Average Sales = ₹25,000
```

---

## 2. Diagnostic Analysis

Answers:

> **Why did it happen?**

Example:

```text
Sales decreased
       ↓
Customer Orders Decreased
       ↓
Product Prices Increased
```

---

## 3. Predictive Analysis

Answers:

> **What is likely to happen?**

Historical data can be analyzed to predict future outcomes.

```text
Historical Data
       ↓
Analysis / Model
       ↓
Future Prediction
```

---

## 4. Prescriptive Analysis

Answers:

> **What should we do?**

Example:

```text
Sales are decreasing
       ↓
Analyze Customer Behavior
       ↓
Identify Problem
       ↓
Recommend Discount
       ↓
Improve Sales
```

---

# 🛠️ Tools & Technologies

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming and Analysis  |
| NumPy            | Numerical Computing       |
| Pandas           | Data Manipulation         |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| Jupyter Notebook | Interactive Analysis      |
| Google Colab     | Cloud-Based Analysis      |
| Excel            | Spreadsheet Analysis      |
| SQL              | Database Analysis         |
| Power BI         | Business Intelligence     |
| Tableau          | Data Visualization        |
| Git              | Version Control           |
| GitHub           | Repository Management     |

---

# 📦 Libraries Used

The major Python libraries used in this repository include:

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
```

---

# 📁 Repository Structure

The repository is organized into different sections:

```text
Data-Analysis/
│
├── README.md
│
├── Python/
│   ├── Basics/
│   ├── Functions/
│   └── File_Handling/
│
├── NumPy/
│   ├── Arrays/
│   ├── Operations/
│   └── Practice/
│
├── Pandas/
│   ├── Series/
│   ├── DataFrame/
│   ├── Data_Cleaning/
│   └── Practice/
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

---

# 🚀 How to Run the Repository

## Step 1: Clone the Repository

```bash
git clone https://github.com/YOUR-USERNAME/Data-Analysis.git
```

## Step 2: Open the Repository

```bash
cd Data-Analysis
```

## Step 3: Create Virtual Environment

```bash
python -m venv venv
```

## Step 4: Activate Virtual Environment

For Windows:

```bash
venv\Scripts\activate
```

## Step 5: Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn jupyter openpyxl
```

## Step 6: Start Jupyter Notebook

```bash
jupyter notebook
```

---

# 💻 Example Data Analysis

Suppose we have a customer dataset:

```text
Customer | Age | City | Purchase
---------------------------------
A        | 21  | Pune | 500
B        | 25  | Mumbai | 900
C        | 20  | Pune | 700
D        | 30  | Delhi | 400
```

### Load Dataset

```python
import pandas as pd

df = pd.read_csv("customers.csv")
```

### View Dataset

```python
print(df.head())
```

### Check Dataset Information

```python
print(df.info())
```

### Statistical Summary

```python
print(df.describe())
```

### Calculate Average Purchase

```python
print(df["Purchase"].mean())
```

### Analyze Purchases by City

```python
print(df.groupby("City")["Purchase"].mean())
```

### Visualize Results

```python
import matplotlib.pyplot as plt

df.groupby("City")["Purchase"].mean().plot(kind="bar")

plt.title("Average Purchase by City")
plt.xlabel("City")
plt.ylabel("Average Purchase")

plt.show()
```

---

# 🧠 Data Analysis Skills

By working on this repository, I am developing the following skills:

* Python Programming
* NumPy
* Pandas
* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis
* Statistical Analysis
* Data Visualization
* Data Interpretation
* Problem Solving
* Analytical Thinking
* SQL
* Excel
* Power BI
* Tableau
* Git
* GitHub

---

# 📈 Learning Roadmap

My Data Analysis roadmap:

```text
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

---

# 🔮 Future Improvements

I will continue improving this repository by adding:

* More Data Analysis exercises
* More real-world datasets
* Advanced Pandas operations
* Advanced EDA projects
* Statistical analysis projects
* SQL projects
* Excel dashboards
* Power BI dashboards
* Tableau dashboards
* End-to-end Data Analysis projects
* Data Science projects
* Machine Learning projects

---

# 🎯 Goal

The long-term goal of this repository is to build strong practical knowledge in **Data Analysis, Data Science, and Machine Learning**.

The focus is not only on writing code but also on understanding:

```text
What happened?
      ↓
Why did it happen?
      ↓
What patterns exist?
      ↓
What may happen next?
      ↓
What should we do?
```

---

# ⭐ Conclusion

Data Analysis is an important skill for converting raw data into useful information.

This repository documents my journey of learning and implementing:

**Python → NumPy → Pandas → Data Cleaning → EDA → Statistics → Visualization → SQL → BI → Real-World Projects**

I will continue updating this repository as I learn new concepts and work on new projects.

---

# 👨‍💻 Author

## Ayush Jugseniye

**Computer Engineering Student**

### Interests

* 📊 Data Analysis
* 📈 Data Science
* 🤖 Artificial Intelligence
* 🧠 Machine Learning
* 🐍 Python
* 🗄️ SQL
* 📊 Business Intelligence

---

# ⭐ Support

If you find this repository useful, please consider giving it a ⭐ on GitHub.

Thank you for visiting my **Data Analysis Repository!** 🚀
