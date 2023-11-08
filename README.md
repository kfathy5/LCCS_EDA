# Lending Club Case Study
> This project shows how EDA solves real business problems. Apart from utilizing EDA techniques, this case study will teach you about risk analytics in banking and financial services and how data is utilized to reduce the risk of losing money when lending to customers.



## Table of Contents
* Understanding the data set
* Data Cleaning
* Data preparation
* Data Analysis 
* The recommendations


## General Information
This organization is the largest online loan marketplace for personal, business, and medical loans. A rapid internet interface lets borrowers get lower-interest loans. 

Lending to ‘risky’ candidates is the biggest source of credit loss for most lending organizations. The lender loses credit when the borrower defaults or flees. Thus, defaulting borrowers cost lenders the most. Customers branded 'charged-off' are 'defaulters’. 

By identifying hazardous loan applicants, credit loss can be reduced. In this case study, EDA is used to identify such applications.

The company needs to know the primary drivers of loan default, or variables that strongly predict default.  This might help the organization assess portfolio and risk. 



## Conclusions
- Applications with a big drop for DTI after 25 should be carefully reviewed.
- Installment majority between 50 and 400 should be given more weight in the decision-making process.
- Applications with emp_length majority at 10+ should be prioritized.
- Loans for debt consolidation purposes should be given preference.
- Preferably accept loan applications with a term of 36 months, as it is the majority.
- Strong positive correlation between loan_amnt and installment should be considered in loan approval decisions.
- Positive correlation between loan_amnt and int_rate should also be considered.




## Technologies Used
- numpy
- pandas
- seaborn
- matplotlib.pyplot
- warnings


