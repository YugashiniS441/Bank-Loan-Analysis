# Bank-Loan-Analysis – Exploratory Data Analysis (EDA)

A data-driven analysis of loan applications to understand patterns in customer behavior, risk factors for defaults, and to improve loan approval decisions. This project is performed entirely in 'Microsoft Excel' using real-world data analytics techniques.

📁 Project Description

This case study focuses on exploring loan application data to identify the key attributes that influence "loan approval" and "repayment". The goal is to:

- Avoid rejecting capable applicants
- Minimize financial risk from defaulters
- Help make better, data-informed lending decisions

📌 Key Objectives

- Identify and handle missing data and outliers
- Analyze class imbalance in target variable
- Perform univariate, segmented, and bivariate analysis
- Explore correlations between customer attributes and loan default risk

 🛠 Tech Stack

- **Microsoft Excel 2021**
  - Pivot Tables
  - Conditional Formatting
  - Charts and Graphs
  - Excel Formulas: `COUNTBLANK()`, `QUARTILE()`, `CORREL()`, etc.

📊 Techniques Used

- **Missing Value Treatment:**  
  Used `COUNTBLANK()` to identify missing values and replaced with median where appropriate. Dropped columns with >30% missing data.

- **Outlier Detection:**  
  Used the **Interquartile Range (IQR)** method to detect outliers and highlighted them with conditional formatting. Created scatter and box plots.

- **Class Imbalance:**  
  Analyzed distribution of defaulters vs non-defaulters using pivot tables and pie charts. Found a significant imbalance:  
  - 92% Non-defaulters  
  - 8% Defaulters

- **Univariate & Bivariate Analysis:**  
  Explored individual and paired attributes like age, income, family status, education, etc., and their relation to the `TARGET` variable.

- **Correlation Analysis:**  
  Used `CORREL()` to study the relationships between key attributes and loan defaults, separately for defaulters and non-defaulters.

 📈 Key Insights

- Majority of applicants are middle-aged, married, and have secondary education.
- Higher loan default rates are observed in low-income and less-educated segments.
- Strong correlations found between:
  - `AMT_Credit` & `AMT_Goods_Price`
  - `AMT_Annuity` & `AMT_Credit`

📎 Dataset & Results

- Data analyzed using Excel with 50,000+ records  
- ➡️ [**View Result Dataset on Google Sheets**](https://docs.google.com/spreadsheets/d/1pfca6H7n-HwTmVV0s5mOG-zUKfrpiO6x/edit?usp=sharing)

 ✅ Outcome

- Learned real-world data analytics using Excel
- Identified risk profiles for defaulters
- Provided actionable insights to improve lending decisions:
  - Focus on income stability and education level
  - Monitor high-risk demographics more closely

🧠 What I Learned

- Cleaning and transforming large datasets in Excel
- Visual storytelling through charts and dashboards
- Statistical thinking using basic Excel functions
- Real-world use of EDA to support business decisions


Feel free to connect with me on [LinkedIn]( https://www.linkedin.com/in/yugashini-s )

