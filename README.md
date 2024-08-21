# Lending Club Case Study
> This is case study about consumer finance company where we have to analyse data and decide on the parameters which will help us on making descision wether to approve loan or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- This is a EDA project where we are dealing with data from a lending organization which has various parameters.
- The Data is from a consumer finanace company where we have close to 39717 borrowers and on basis of this data we have to form insights.
- Based on the analysis and insights we have to decide whether to approve the loan or not.
- We are using loan.csv dataset which has more than 111 columns and 39717 rows.

## Conclusions
Considering all the above analysis multiple factors can be taken into account while accepting or rejecting the loan application.
1. Term --> duration of the loan ( lesser the duration lower the chances of defaulters)
2. Interest rate (lesser the interest rate higher the chances of loan repayment)
3. Purpose for which the loan is availed- debt_consolidation,credit_card, home_improvement and small_business are major categories where loss is more.
4. addr_state: Few states like CA (California) and FL (Florida) has high loan defaulters
5. Years of employment: We saw 10years and <1 years having high count, this applies to Fully paid and charged off too.
6. annual_inc --> annual income (higher the income higher the chances of repayment)
7. Grades: Loan grade A, B have higher chances of repayment and C,D,E,F,G grades have maximum defaulters.
8. verification_status: We observe that defaulters are more ratio wise in case of 'Verified'and 'Source Verified' compared to 'Not Verified'. So we can conclude income verification or income source verification does not gurantee us if the loan will be repaid
9. loan_amnt: Higher the loan higher the chances of loan default


## Technologies Used
- jupyter notebook - 7.0.8
- matplotlib library
- seaborn library - Seaborn version: 0.12.2
- pandas - Pandas version: 2.1.4
- numpy - NumPy version: 1.26.4

## Acknowledgements
- This project was done as part of UpgradC66 Batch - ML/AI project under EDA module.


## Contact
Created by [@shamanthn8904@gmail.com] and [@] - feel free to contact us!

