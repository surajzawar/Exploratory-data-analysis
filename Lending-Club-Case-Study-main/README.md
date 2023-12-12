# Lending-Club-Case-Study
Solving this assignment will give you an idea about how real business problems are solved using EDA. In this case study, apart from applying the techniques you have learnt in EDA, you will also develop a basic understanding of risk analytics in banking and financial services and understand how data is used to minimise the risk of losing money while lending to customers.

## Table of Contents
*[General Info] : Python Notebook with data analysis and visiual representation
*[Technologies Used] : Python
*[Conclusions] : Lending Case Study.pdf
*[Acknowledgements]: Upgrad

## General Information
Business Understanding
You work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
1.If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
2.If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
The loan data contains the information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. In this case study, i am using EDA to understand how consumer attributes and loan attributes influence the tendency of default.


When a person applies for a loan, there are two types of decisions that could be taken by the company:
        1.Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
               1.Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
               2.Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
               3.Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan
        2.Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset).

## Conclusions
Refrain
	Refrain from giving Huge Loan Amount loans.
Reduce
	Reduce giving loans for Small Business purpose.
Avoid
	Avoid giving loans for users who have multiple open credit open accounts.
Stop
	Stop approving loans foe people with bad record OR have lower grade.
Reduce
	Reduce giving loans to user with high DTI ratio.


## Technologies Used
Python 3.3
Jupyter Notebook

## Acknowledgements
Upgrad Faculty
Team members

## Contact
Pooja pal
Suraj Zawar
https://github.com/ppcoder0204/Lending-Club-Case-Study.git


