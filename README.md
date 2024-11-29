# FUTURE_DS_01
## Titanic Dataset Analysis
This repository contains a Jupyter Notebook demonstrating the process of data cleaning and exploratory data analysis (EDA) on the Titanic dataset. The goal of this analysis is to uncover patterns, trends, and relationships in the data, particularly regarding passenger survival rates.

**Dataset Description**

The Titanic dataset provides information about passengers, including demographic details, ticket class, fare, and survival status. The key variables in the dataset are as follows:

1. **PassengerId:** Unique identifier for each passenger.
2. **Survived:** Survival status (0 = No, 1 = Yes).
3. **Pclass:** Ticket class (1 = First, 2 = Second, 3 = Third).
4. **Name:** Name of the passenger.
6. **Sex:** Gender of the passenger.
7. **Age:** Age of the passenger.
8. **SibSp**: Number of siblings/spouses aboard.
9. **Parch:** Number of parents/children aboard.
10. **Ticket:** Ticket number.
11. **Fare:** Fare paid for the ticket.
12.**Cabin:** Cabin number
 13.**Embarked:** Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton).


   ## Key Steps in the Notebook
### 1. Data Loading and Inspection
Loaded the dataset using pandas.
Inspected data structure, including column names, data types, and missing values.
### 2. Data Cleaning
Renamed incorrectly labeled columns.
Imputed missing values for Age and Embarked.
Standardized column names and dropped unnecessary or redundant columns.
Ensured no duplicate rows.
### 3. Exploratory Data Analysis (EDA)
Analyzed the following aspects:

1. Distribution of passenger ages and fares.
2. Survival rates across gender, class, and embarkation ports.
3. Correlation between numerical variables using a heatmap.
4. Visualized relationships between survival and key features like age and class.

### 4. Key Findings
1. **Survival Rate:** The overall survival rate is significantly lower than the death rate.
2. **Gender and Survival:** Females had a much higher survival rate compared to males.
3. **Class and Survival**: First-class passengers had the highest survival rate, followed by second class, with third class having the lowest.
4. **Age and Survival:** Younger passengers had a slightly higher chance of survival.
