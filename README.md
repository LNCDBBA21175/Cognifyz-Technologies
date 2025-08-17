# 📊 Investment Preferences Dataset Analysis & Visualization

### 🚀 Project Overview
This project analyzes the **Investment Preferences Dataset** to explore patterns in investment behavior, objectives, and decision-making factors among individuals.  
It includes **data cleaning, processing, and visualization** to identify trends in various investment avenues.

## Task 1 :- Data Overview
### 📌 Objective
The goal of this dataset is to analyze investment preferences, objectives, and decision-making factors among different individuals.

### - 📂 Dataset Overview
The dataset contains information about investors, including:

- Rows: 40
- Columns: 24 
- Data Types:
  - Numeric: 8 columns (e.g., Age, Mutual_Funds, Equity_Market, Debentures)
  - Categorical: 16 columns (e.g., Gender, Investment_Avenues, Purpose, Duration)
  
### - 🛠 Technologies Used
- **🐍 Python**
- **Pandas** (Data manipulation)  
- **Matplotlib** & **Seaborn** (Data visualization)  
- **Jupyter Notebook**

### - 📊 Column Categories
- Demographics: Gender, Age
- Investment Types: Mutual_Funds, Equity_Market, Debentures, Government_Bonds, Fixed_Deposits, PPF, Gold
- Preferences & Objectives: Investment_Avenues, Factor, Objective, Purpose, Duration, Savings Objectives
- Reasons for Choosing Instruments: Reason_Equity, Reason_Mutual, Reason_Bonds, Reason_FD
- Sources of Information: Source

## Task 2 :- Gender Distribution
### 📌 Objective: 
Visualize gender distribution in the dataset.

### - 📈 Gender Distribution:
**Bar Chart :**  

![Gender Bar Chart](https://github.com/LNCDBBA21175/Cognifyz-Technologies/blob/2acdb739b56d922a3fed3714433519e960e4d186/bar%20graph.png)

**Pie Chart :**

![Gender Pie Chart](https://github.com/LNCDBBA21175/Cognifyz-Technologies/blob/5feca0eedac213dddf3b31cc6d015b32a470eef0/pie%20chart.png)

### - 🔍 Insights
- The dataset is **male-dominated**, with **62.5% males** and **37.5% females**.  
- Indicates that **male respondents are more actively represented** in the investment preference study.  
- This skew may influence other insights, such as preferred investment avenues and objectives.  
- Further analysis is needed to check if **gender impacts investment choices and risk appetite**.

## Task 3 :- Descriptive Statistics
### 📌 Objective :
Present basic statistics for numerical columns.

### - Identify Numerical Columns – Review the dataset to find numerical data (e.g., Age, Income).
### - Perform Calculations – Apply statistical functions to summarize the data:
- Mean – Average value of the column.
- Median – Middle value of the column.
- Standard Deviation – Spread/variation of the data.

### - Outcome: A statistical summary table that provides insights into the central tendency and variability of key numerical features.

## Task 4: Most Preferred Investment Avenue
### 📌 Objective :
Identify the most preferred investment avenue.

### - Analyze Investment Avenues – Examine the dataset column that contains information about different investment options (e.g., Equity, Mutual Funds, Real Estate, Gold, etc.).
### - Frequency Analysis – Count the frequency of each investment avenue to determine the most preferred option.

### - Outcome: A frequency distribution of all investment avenues, highlighting the most commonly preferred option.

## Task 5: Reasons for Investment
### 📌 Objective :
The main goal of this analysis is to understand investor preferences and summarize the reasons behind their investment choices using the provided dataset.

### - Identify the Most Preferred Investment Avenue
- Extracted the Investment_Avenues column.
- Performed frequency analysis using value_counts().
- Created bar charts to visualize the popularity of different investment avenues.

### - Analyze and Summarize Reasons for Investment Choices
- Explored reason columns:
  - Reason_Equity
  - Reason_Mutual
  - Reason_Bonds
  - Reason_FD
- Conducted frequency analysis for each reason.
- Created visualizations:
  - Bar charts showing top reasons for each avenue.
  - Word Cloud combining all reasons for an overall summary.

### - 📊 Visualizations
- Bar Charts – Display the top 3 reasons for each investment type.
- Word Cloud – Highlights the most common reasons across all investment avenues.
  
**Top Reasons for Equity Investment :**  

![Equity Investment Bar Chart](https://github.com/LNCDBBA21175/Cognifyz-Technologies/blob/dc965d9cd677a798daa5b20c7e775f20b2d5f9c7/Equity%20Investment%20Bar%20Chart.png)

**Top Reasons for Mutual Investment :**  

![Mutual Investment Bar Chart](https://github.com/LNCDBBA21175/Cognifyz-Technologies/blob/e82059c2b7e7991ab03005e8b93e3c8d6ad6d82f/Mutual%20Investment%20Bar%20Chart.png)

**Top Reasons for Bond Investment :**  

![Bond Investment Bar Chart]()

## ▶ How to Run the Project
https://github.com/LNCDBBA21175/Cognifyz-Technologies.git
