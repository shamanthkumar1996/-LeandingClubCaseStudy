# Lending Club Case Study
> This is case study about consumer finance company where we have to analyse data and decide on the parameters which will help us on making descision wether to approve loan or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This is a EDA project where we are dealing with data from a lending organization which has various parameters.
- The Data is from a consumer finanace company where we have close to 40000 borrowers and on basis of this data we have to form insights.
- Based on the analysis and insights we have to decide whether to approve the loan or not.
- We are using loan.csv dataset which has more than 100 columns and 40000 rows.

## Conclusions
- Based on the analysis done via various techniques: Univariate anyalysis, Bivariate analysis we came to conclusion that interest rate,annual_inc, addr_state, grade, term, loan_amnt purpose are important factors for deciding on set borrowers who defaulting on loan payment.
- Term: duration of the loan ( lesser the duration lower the chances of defaulters)¶
- Interest rate (lesser the interest rate higher the chances of loan repayment)
-  Purpose for which the loan is availed- debt_consolidation,credit_card, home_improvement and small_business are major categories where loss is more.
- addr_state: Few states like CA (California) and FL (Florida) has high loan defaulters
- Grades: Loan grade A, B have higher chances of repayment and C,D,E,F,G grades have maximum defaulters.
- annual_inc --> annual income (higher the income higher the chances of repayment)
- loan_amnt: Higher the loan higher the chances of loan default.


## Technologies Used
- jupyter notebook - 7.0.8
- matplotlib library
- seaborn library - Seaborn version: 0.12.2
- pandas - Pandas version: 2.1.4
- numpy - NumPy version: 1.26.4

## Acknowledgements
- This project was done as part of Upgrad64 Batch - ML/AI project under EDA module.


## Contact
Created by [@prashanthector] and [@pgk99] - feel free to contact us!

