## Loan Data Analysis Project
This project analyzes the loan data of a bank for a large number of Customers. In recent years, banks are playing an indespensible role to lend people for various purposes. Due to working in the Bank, I felt interested in analyzing the loan data to find the corelation among purposes, interest rate and installment.  

The project focuses on imported data from csv file, followed by analysis with basic formulas, and seeks to explain the findings from the study.
## Data sources
Data was obtained from the Kaggle loan_data and the dataset contains 14 columns and 9578 rows.

****************************************************************************************************

## Queries and Case:   

.head  

.shape  

.index  

.columns  

.dtypes  

.unique()  

.nunique()  

.count()  

.value_counts()  

.info()  

Q1: Find all the unique "int.rate" values in the data?  

Q2: Find the number of times when the purpose is "educational"?  

Q3: Find the number of times when the "inq.last.6mths" is exactly 3?  

Q4: Find all the null values?  

Q5: Rename the column name "purpose" to "loan_purpose"?  

Q6: What is the mean value of "revol.bal"?  

Q7: What is the standard deviation of "installment"?  

Q8: What is the Variance of "revol.util"?  

Q9: Find all instances when "credit" was recorded?  

Q10: Find all the instances when "fico is above 700" and "not.fully.paid is 1"?  

Q11: What is the mean value of each column against each "loan_purpose"?  

Q12: What is the minimum and maximum value of each column against each "loan_purpose"?  

Q13: Show all the records where "loan_purpose" is home_improvement?  

Q14: Find all instances when "loan_purposes is small_business" or "dti is above 15"?  

Q15: Find all Instances when: a) loan_purpose is home_improvement and revol.bal > 300000 or b) days.with.cr.line > 6000?
