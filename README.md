# Data-Cleaning-Pipeline-for-SaaS-Dataset

## 📌 Overview

This project is a Python-based data cleaning pipeline created for the **Module 1 Assessment** of the Advanced Data Science Program.

The program works with a SaaS customer dataset and performs data cleaning, validation, analysis, and file generation using core Python concepts such as loops, functions, dictionaries, object-oriented programming, exception handling, and file handling.

---

## 🚀 Features

### 📋 Display Dataset
- Displays all customer records in a readable format using a `for` loop.

### ➕ Add New Customers
- Allows users to add new customer records.
- Automatically generates the next customer ID.
- Stores the new records in the dataset.

### 👤 Object-Oriented Programming
A `SaaSCustomer` class is implemented with methods to:
- Validate customer information
- Handle invalid data
- Display customer details

### 🧹 Data Cleaning
The project cleans the dataset by:
- Replacing missing customer names with **"Unknown Customer"**
- Replacing missing usage hours with **0**
- Converting valid monthly fees to `float`
- Setting invalid monthly fees to `None`
- Standardizing multiple date formats into **YYYY-MM-DD**

### 🔄 Duplicate Removal
- Removes duplicate customer records based on **Customer ID**.

### 📊 Data Analysis
The program calculates:
- Total number of customers
- Average monthly fee
- Total usage hours
- Subscription plan distribution

### ⚠️ Low Usage Detection
- Identifies customers with usage hours below **50**.

### 📑 Unique Plans
- Extracts all unique subscription plans using a Python `set`.
- Displays the plans in alphabetical order.

### 💾 File Handling
The cleaned dataset is exported to:
- `saas_customers_cleaned.csv`

A subscription summary is exported to:
- `plan_summary.txt`

Both files are created using Python file handling with `try`, `except`, `else`, and `finally` blocks.

---

## 🛠️ Technologies Used

- Python
- Google Colab
- datetime module

---

## 📚 Python Concepts Applied

- Variables
- Lists
- Dictionaries
- Loops
- Functions
- Conditional Statements
- Object-Oriented Programming (Classes & Objects)
- Exception Handling
- File Handling
- Date Formatting
- Sets

---

## 📁 Project Files

```
M1_Assessment.ipynb
saas_customers_cleaned.csv
plan_summary.txt
README.md
```

---

## 📈 Output

The project generates:

- Cleaned SaaS customer dataset (`saas_customers_cleaned.csv`)
- Subscription plan summary (`plan_summary.txt`)
- Summary statistics
- Low-usage customer report
- Unique subscription plan list

---

## 👩‍💻 Author

**Varsha A**

AI & ML Graduate | Junior Data Scientist & Machine Learning Engineer | Python | SQL | Excel | 
Power BI | Prompt Engineer | Front-End Developer 
