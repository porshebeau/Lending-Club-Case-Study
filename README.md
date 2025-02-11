# Lending Club Case Study - UPGRAD



## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- I assume to work for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to make a decision for loan approval based on the applicant’s profile. Two types of risks are associated with the bank’s decision:
-   If the applicant is likely to repay the loan, then not approving the loan results in a loss of business to the company
-   If the applicant is not likely to repay the loan, i.e. he/she is likely to default, then approving the loan may lead to a financial loss for the company

  The data given below contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.
  In this case study, I will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.
    
    When a person applies for a loan, there are two types of decisions that could be taken by the company:
      Loan accepted: If the company approves the loan, there are 3 possible scenarios described below:
        Fully paid: Applicant has fully paid the loan (the principal and the interest rate)
        Current: Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
        Charged-off: Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 

      Loan rejected: The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
 

Business Objectives
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment. 

To develop our understanding of the domain, I am advised to independently research a little about risk analytics (understanding the types of variables and their significance should be enough).

Data Set:
It contains the complete loan data for all loans issued through the time period 2007 t0 2011. data dictionary which describes the meaning of these variables is also attached.


## Conclusions
- Conclusion 1 from the analysis
- Conclusion 2 from the analysis
- Conclusion 3 from the analysis
- Conclusion 4 from the analysis

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
python == 3.10.5
numpy==2.0.2
pandas==2.2.2
seaborn==0.13.2
re==2.2.1
platform==1.0.8


## Acknowledgements
- This project was inspired by Upgrad and I thank Saumya Singh <its.saumyah@gmail.com> for her unwavering help and support.

## Contact
Created by [@Venkadeah-kannan]- feel free to contact me!

