# 📊 Bank Loan Analysis
  Bank Loan Analysis using Excel, MySQL, Power BI, and Tableau.
  
  This project aims to examine bank loan data to gain insights into loan performance and customer behavior. 
  Leveraging powerful tools like Excel, MySQL, Power BI, and Tableau, we conduct advanced analytics and create interactive visualizations to support data-driven decision-making.

---

# 📁 Data Sources
    The dataset used for this analysis comprises historical bank loan data, including:
      1. 🧑‍🤝‍🧑 Customer information
      2. 💵 Loan amount
      3. 📝 Purpose of the loan
      4. 💼 Invested fund
      5. 🔄 Repayment status
      6. 📉 Credit scores
      7. 🎓 Loan grade And other relevant attributes, The data is sourced from the bank's 
            internal database and stored in a MySQL database for efficient access and manipulation.

---

# 🔍 Analysis Process 
  1. 🧹Data Preprocessing with Excel:
       - Data Cleaning: Removed duplicates, handled missing values, and formatted data types to ensure data integrity.
       - Exploratory Data Analysis (EDA): Identified patterns, outliers, and trends in the loan data.
  
  2. 🗄️Database Management with MySQL:
       - Data Import: Preprocessed loan data was imported into a MySQL database for efficient storage and retrieval.
       - SQL Queries: Created queries to perform data transformations, aggregations, and calculations necessary for the analysis.                                       
         Note: Datasets were added using the insert data wizard.
  
  3. 📊Interactive Visualization with Power BI:
       - Data Connection: Connected Power BI to the MySQL database to import the loan data.
       - Dashboard Design: Designed interactive dashboards and reports to visualize key metrics such as loan portfolio composition, delinquency rates, and customer demographics.
       - User Interaction: Implemented slicers, filters, and drill-down functionalities for dynamic data exploration.
 
  4. 📈Advanced Analytics and Reporting with Tableau
       - Advanced Analytics: Leveraged Tableau for predictive modeling, cohort analysis, and geographical mapping of loan performance.
       - Dashboard Creation: Created visually appealing and insightful dashboards to present findings and recommendations to stakeholders.
       - Integration: Integrated Tableau dashboards with Power BI reports for a comprehensive view of the analysis results.

---

# Columns description:
    1. id: Unique identifier for each loan.
    2. member_id: Unique identifier for each member (customer).
    3. loan_amnt: The amount of money loaned to the member.
    4. grade: The loan grade is assigned based on the risk of the loan.
    5. sub_grade: A more detailed breakdown of the loan grade.
    6. home_ownership: The homeownership status of the member (e.g., RENT, OWN, MORTGAGE).
    7. verification_status: Indicates whether the income of the borrower was verified.
    8. issue_d: The date when the loan was issued.
    9. loan_status: The current status of the loan (e.g., Fully Paid, Charged Off).
    10. addr_state: The state of the borrower's address.
    11. Year: The year when the loan was issued.
    12. Revol Bal: The revolving balance amount (amount owed on revolving credit accounts).
    13. total_pymnt: The total amount of payment received to date for the loan.
    14. last_pymnt_d: The date of the last payment made.
    15. last_pymnt_amnt: The amount of the last payment made.
    16. last_credit_pull_d: The date when the borrower's credit was last pulled.
      
---

# 📊 Key Performance Indicators (KPIs)
  1. Year-wise Loan Amount Statistics: Analyze loan amounts distributed each year to identify trends and growth patterns.
  2. Grade and Sub-grade-wise Revolving Balance (revol_bal): Examine the revolving balance categorized by loan grades and sub-grades to assess risk levels.
  3. Total Payment Comparison: Compare total payments for verified vs. non-verified status loans.
  4. State-wise and Last Credit Pull Date-wise Loan Status: Analyze loan status by state and the last credit pull date to identify regional performance and trends.
  5. Home Ownership vs. Last Payment Date Statistics: Evaluate the relationship between home ownership status and the last payment date to understand customer repayment behavior.

---

# 🏆Key Findings:
  - Banks need to understand the demographics of customers taking loans, such as age, income level, occupation, and credit score. This information can help the bank design targeted loan products and marketing strategies.
  - By analyzing the most common purposes for which customers are taking loans like home purchases, car loans, education, personal use, etc.
  - This helps to understand customer needs, accordingly, banks can offer loan products.
  - By examining the range of interest rates and loan terms offered to customers, banks can provide insights into the competitiveness of the loan offerings and how they compare with other financial institutions.
    
---

# 📈 Conclusion
 This analysis provides comprehensive insights into the bank's loan portfolio, enabling stakeholders to make informed decisions based on data-driven insights. The combination of Excel, MySQL,
 Power BI and Tableau ensure thorough data preprocessing, efficient database management, and advanced analytics, resulting in valuable findings and actionable recommendations.
