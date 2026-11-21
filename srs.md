# SOFTWARE REQUIREMENTS SPECIFICATION (SRS)

## Project Title: Titanic Disaster Analysis Using Python

**Project Type:** Data Analysis Project  
**Programming Language:** Python  
**Development Environment:** Visual Studio Code  
**Dataset Source:** Kaggle  
**Document Type:** Software Requirements Specification  
**Version:** 1.0

---

# 1. INTRODUCTION

## 1.1 Purpose

The purpose of this project is to analyse the Titanic disaster dataset using Python. The project aims to identify patterns and relationships between passenger information and their survival chances.

The analysis helps us understand how factors such as age, gender, passenger class, fare and family size influenced passenger survival.

## 1.2 Project Scope

This project focuses on analysing historical passenger data from the Titanic disaster.

The project includes:
- Collecting data from Kaggle.
- Loading the dataset using Python.
- Cleaning and preprocessing the data.
- Handling missing values.
- Performing Exploratory Data Analysis (EDA).
- Creating graphs and visualisations.
- Identifying important patterns and insights.

## 1.3 Project Objectives

The main objectives are:

1. To understand the Titanic passenger dataset.
2. To analyse passenger survival rates.
3. To compare survival rates based on gender and age.
4. To study the relationship between passenger class and survival.
5. To identify important factors affecting survival.
6. To improve practical knowledge of Python and data analysis.

# 2. OVERALL DESCRIPTION

## 2.1 Product Perspective

This project is a standalone data analysis application developed using Python. It uses a publicly available Titanic dataset from Kaggle.

The project processes the dataset and generates meaningful statistical information and visual representations.

## 2.2 Product Functions

The main functions of the project are:

- Dataset loading.
- Data inspection.
- Data cleaning.
- Missing value handling.
- Statistical analysis.
- Data visualisation.
- Survival pattern identification.

## 2.3 User Characteristics

The intended users of this project include:

- Students learning Python.
- Beginners in Data Science.
- Data Analysis learners.
- Educational institutions.

# 3. HARDWARE AND SOFTWARE REQUIREMENTS

## 3.1 Hardware Requirements

- Processor: Intel Core i3 or above.
- RAM: Minimum 4 GB.
- Storage: Minimum 500 MB free space.
- System: Desktop or Laptop.

## 3.2 Software Requirements

- Operating System: Windows 10/11 or Linux.
- Programming Language: Python 3.
- IDE: Visual Studio Code.
- Dataset Source: Kaggle.
- Libraries:
  - Pandas
  - NumPy
  - Matplotlib
  - Seaborn

# 4. FUNCTIONAL REQUIREMENTS

The system should fulfil the following functional requirements:

**FR-01: Data Collection**

The system shall use the Titanic dataset downloaded from Kaggle.

**FR-02: Data Loading**

The system shall load the dataset into Python using Pandas.

**FR-03: Data Inspection**

The system shall display dataset information, column names, data types and statistical summaries.

**FR-04: Data Cleaning**

The system shall identify and handle missing or inconsistent values.

**FR-05: Data Analysis**

The system shall analyse passenger survival based on different characteristics.

**FR-06: Data Visualisation**

The system shall generate charts and graphs to represent the analysis results.

**FR-07: Result Interpretation**

The system shall help users understand important patterns in passenger survival.

# 5. NON-FUNCTIONAL REQUIREMENTS

**5.1 Performance**

The system should process the Titanic dataset efficiently.

**5.2 Usability**

The code should be easy to understand and execute.

**5.3 Reliability**

The system should produce consistent results when executed with the same dataset and processing steps.

**5.4 Maintainability**

The code should be properly structured so that future improvements can be made easily.

**5.5 Portability**

The project should be executable on systems that support Python and the required libraries.

# 6. DATASET DESCRIPTION

The dataset used in this project is obtained from Kaggle.

The Titanic dataset contains passenger-related information.

Important attributes include:

| Attribute | Description |
|---|---|
| PassengerId | Unique passenger ID |
| Survived | Survival status (0 = No, 1 = Yes) |
| Pclass | Passenger class |
| Name | Passenger name |
| Sex | Passenger gender |
| Age | Passenger age |
| SibSp | Number of siblings/spouses aboard |
| Parch | Number of parents/children aboard |
| Ticket | Ticket number |
| Fare | Ticket fare |
| Cabin | Cabin number |
| Embarked | Port of embarkation |

# 7. SYSTEM DEVELOPMENT METHODOLOGY

The project follows these steps:

1. Data Collection – Downloading the dataset from Kaggle.
2. Data Loading – Importing the dataset into Python.
3. Data Exploration – Understanding the dataset structure.
4. Data Cleaning – Handling missing values and inconsistencies.
5. Data Analysis – Performing statistical analysis.
6. Data Visualisation – Creating graphs and charts.
7. Result Interpretation – Understanding the findings.

# 8. TOOLS AND TECHNOLOGIES USED

**Python:** Main programming language used for data analysis.

**Pandas:** Used for data manipulation and cleaning.

**NumPy:** Used for numerical operations.

**Matplotlib:** Used for creating graphs and charts.

**Seaborn:** Used for statistical data visualisation.

**Kaggle:** Used as the source of the Titanic dataset.

**Visual Studio Code:** Used as the development environment.

# 9. EXPECTED OUTPUT

The expected outputs of the project include:

- Passenger survival statistics.
- Gender-wise survival comparison.
- Age-wise survival analysis.
- Passenger class-wise survival analysis.
- Graphical representation of survival patterns.
- Identification of important factors associated with survival.

# 10. FUTURE ENHANCEMENTS

The project can be improved in the future by:

1. Implementing Machine Learning algorithms.
2. Predicting passenger survival using classification models.
3. Creating an interactive dashboard.
4. Adding more advanced statistical analysis.
5. Developing a web-based interface for users.

# 11. CONCLUSION

The Titanic Disaster Analysis project demonstrates how Python can be used to analyse real-world historical data.

By using libraries such as Pandas, NumPy, Matplotlib and Seaborn, the project helps identify patterns and relationships between passenger characteristics and survival outcomes