# Lending Club - Case Study
> Lending Club is a prominent consumer finance marketplace that connects borrowers with investors. The company provides a range of loans to urban customers, including personal, business, and medical loans. When evaluating a loan application, Lending Club must make a critical decision based on the applicant's profile.

1. **Loss of Business**: If an applicant who is likely to repay the loan is not approved, the company misses out on potential revenue and business growth.
2. **Financial Risk**: If an applicant who is likely to default is approved, the company faces financial losses due to non-repayment.

### Data Description
The dataset contains historical information about loan applicants and their loan statuses. The statuses are:
- **Fully Paid**: The applicant has successfully repaid the entire loan.
- **Current**: The loan is still active and being repaid by the applicant.
- **Charged-Off**: The applicant has defaulted on the loan and has not made payments for an extended period.

Rejected loan applications are not included in the dataset, as there is no transaction history for these applicants.

## Business Objectives

### Problem Statement
The company faces significant credit loss when borrowers default on their loans. Identifying high-risk borrowers who are likely to default is essential to minimizing financial losses.

### Analysis Goal
The objective of this case study is to use Exploratory Data Analysis (EDA) to uncover patterns and identify key factors that predict loan default. By understanding these factors, Lending Club can:

- **Reduce Credit Loss**: Minimize the number of loans granted to high-risk individuals, thereby reducing potential financial losses.
- **Optimize Loan Approval**: Make informed decisions about loan approvals, amounts, and interest rates.

### Key Sources of Credit Loss
1. **Applicants Likely to Repay**: Rejecting these applicants leads to lost business opportunities and potential revenue.
2. **Applicants Likely to Default**: Approving these applicants results in financial losses due to non-repayment.

By accurately identifying these two types of applicants, Lending Club can enhance its lending strategy, reduce financial risk, and improve profitability. Understanding the driving factors behind loan defaults will support better portfolio management and risk assessment, leading to more effective decision-making in loan management.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The project focuses on analyzing loan data to identify patterns and factors influencing loan defaults. By examining various attributes and their relationships with default rates, the aim is to enhance risk assessment and improve decision-making processes for loan approval.
- Loan default is a significant issue impacting the overall portfolio of the company. Understanding the factors that contribute to loan defaults is crucial for mitigating risks and optimizing lending strategies. This project uses data analysis to uncover insights into borrower behavior and loan characteristics.
- The primary business problem addressed is to identify key factors that predict loan defaults. By analyzing the dataset, the project seeks to determine how different attributes like dti, interest, loan-to-income, credit line age, income, loan amount, and others important variables impact the likelihood of default. This information will help in refining lending criteria and reducing financial losses from defaults.
- The dataset used in this project is loan.csv which contains information on various loan attributes, including loan amount, interest rate, income, credit history, and loan status. It comprises columns related to borrower details and loan characteristics, with a focus on analyzing historical loan performance and default trends.


## Conclusions
- Higher DTI implies Higher Charge Off % 
- Higher Revolving Utilization implies Higher Charge Off % 
- Higher Loan Amount greater then $12,000 implies Higher Default Risk
- Higher Interest Rates implies Higher Default %
- Higher the Installment beyond the 60% quartile, Higher the Charge Off %
- Higher the Loan-to-Income (LTI), higher the risk.
- Higher the Public Record Bankruptcies , higher is the risk.
- Higher the missing employee records %, higher is the default rate.
- Higher Annual Income implies Lower Default Risk
- Lower the Credit Line Age, Higher the Default Rate




## Technologies Used
- Python - 3.12
- seaborn - 0.12.2
- matplotlib - 3.8.0
- pandas -  2.1.4
- numpy -  1.26.4


## Acknowledgements
Give credit here.
- This project was inspired by Upgrad - IIIT Bangalore.


## Contact
Created by [@ramyap-learnspace] / [@prtmoswal] - feel free to contact us!
