# Lending Club Case Study
<div align="center">
    <img src="images/LC_Image.jpg" width="600px"</img> 
</div>

> A consumer finance company specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. 
> 
> Two types of risks are associated with the bank’s decision:
>* If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
>* If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company
>
> The aim is to identify patterns from the given dataset which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc. Using Exploratory Data Analysis, such loan applicants needs to be analysed and identify the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information
- Using EDA understand how consumer attributes and loan attributes influence the tendency of default.
- Loan dataset has list of appoved applicants and their history. They are categorised as below:
    * Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
    * Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
    * Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 


## Conclusions
- Higher Interest Rate : 
    - Rate of interest increases year-on-year
    - Borrowers with higher Interest Rate (>=11%) are prone to default, irrespective of the category/segment they belong to.
- Higher Loan Amount :
    - Highly experienced borrowers are given loan with higher amount, hence are prone to default.
    - Higher loan amount sanctioned for borrowers with Mortgaged houses or houses in Other category are prone to default, compared to the borrowers with own house or rented house.
    - Higher loan amount given for small business purpose are less likely to repay loan.
    - Higher loan amount given to Income Grades 'F' and 'G' borrowers are prone to default.
- Higher Loan Tenure :
    - Higher interest rate for long tenure loan have more chances to default.
    - Higher loan amount for long tenure loan have more chances to default.



## Technologies Used
- python - version 3.8.5
- pandas - version 1.1.3
- numpy - version 1.19.2
- matplotlib - version 3.3.2
- seaborn - version 0.11.0


## Contact
* Ambily M [@mambily]
* Subhash G [@SubhashG05]

Feel free to contact us!
