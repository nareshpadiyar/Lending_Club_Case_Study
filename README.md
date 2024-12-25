# Lending Club Case Study

## Table of Contents

- [General Info](#general-information)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)
- [Collaborators](#collaborators)


## General Information
### Problem
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:

- If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
- If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

### Objective
The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

### Constraints
When a person applies for a loan, there are two types of decisions that could be taken by the company:
Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:

- Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
    - Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
    - Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
- Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.).


## Conclusions
- 1. There has been a positive trend in loan applications from 2007 to 2011. The company should capitalize on the market's growth trend by meeting the increased demand.
- 2. Highest number of loan applications are seen in the month of December. Possibly due to holiday season Company can use this trend and create new marketing strategy.
- 3. Grades B, C and D have a high possibility of defaulting and hence needs stricter risk assessment.
- 4. Sub Grades B3, B4 and B5 have a high possibility of defaulting and hence needs stricter risk assessment.
- 5. Company should carefully evaluate loan applications applied for debt consolidation purpose.
- 6. Company should evaluate the home ownership status of the loan applicant to access housing stability, and it impact on the applicant's ability to repay the loan.
- 7. It has been seen that verified applicants were the highest in loan defaulters. Company needs consider improvising on their verification process.
- 8. It has been seen that highest number of defaulter belong to CA, NY and FL states. Company should consider implementing stricter risk assessment for these states.
- 9. Loan applicants with short term, 36 months term have been seen defaulting more compared to long term, 60 months tenure. Company can think of increasing the interest rates for short term loans.



## Technologies Used

- [Python](https://www.python.org/)
- [Matplotlib](https://matplotlib.org/)
- [Numpy](https://numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Seaborn](https://seaborn.pydata.org/)


## Collaborators
Created by [@nareshpadiyar](https://github.com/nareshpadiyar)

Repository link: https://github.com/nareshpadiyar/Lending_Club_Case_Study
Following files has been included as a part of solution:
 1. README.md file
 2. Naresh_Padiyar.ipynb 
 3. Naresh_Padiyar.pdf
 4. Loan.csv file
