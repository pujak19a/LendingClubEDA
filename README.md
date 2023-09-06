### LendingClub Case study Exploratory Data Analysis
> This Assignment is about finding the data insights from loan data from Lending Club, to apply lower the number of Charged Off loans.

# Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

## General Information

LendingClub is a financial services company headquartered in San Francisco, California. LendingClub is an online financial service that connects borrowers with loans that fit their needs. It works best for borrowers with good to excellent credit who are looking for personal loans or debt consolidation.

LendingClub began offering loans in 2007 as a peer-to-peer online lender and has lent more than $85 billion in the years since. It’s also expanded its banking services to checking and savings accounts, and has 4.7 million members, making it one of the nation’s biggest online banks.

  
### Business Understanding

This work is for a consumer finance company which specialises in lending various types of loans to urban customers. When the company receives a loan application, the company has to <b>make a decision for loan approval based on the applicant’s profile.</b> Two types of risks are associated with the bank’s decision:
<ul>
<li>
If the applicant is <b>likely to repay the loan</b>, then not approving the loan results in a loss of business to the company
</li>
<li>
If the applicant is <b>not likely to repay the loan</b>, i.e. he/she is likely to default, then approving the loan may lead to a <b>financial loss</b> for the company
</li>
</ul>
 

The loan data given contains information about past loan applicants and whether they ‘defaulted’ or not. The aim is to identify patterns which indicate if a person is likely to default, which may be used for taking actions such as denying the loan, reducing the amount of loan, lending (to risky applicants) at a higher interest rate, etc.

In this case study, we will use EDA to understand how consumer attributes and loan attributes influence the tendency of default.

<img src="Loan_image.png" />

When a person applies for a loan, there are two types of decisions that could be taken by the company:

<ol>
<li><b>Loan accepted:</b> If the company approves the loan, there are 3 possible scenarios described below:
<ul>
<li><b>Fully paid:</b> Applicant has fully paid the loan (the principal and the interest rate)
</li>
<li><b>Current:</b> Applicant is in the process of paying the instalments, i.e. the tenure of the loan is not yet completed. These candidates are not labelled as 'defaulted'.
</li>
<li><b>Charged-off:</b> Applicant has not paid the instalments in due time for a long period of time, i.e. he/she has defaulted on the loan 
</li>
</ul>
</li>
<li><b>Loan rejected:</b> The company had rejected the loan (because the candidate does not meet their requirements etc.). Since the loan was rejected, there is no transactional history of those applicants with the company and so this data is not available with the company (and thus in this dataset)
</li>
</ol>


### Business Objective
This company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface. 

 

Like most other lending companies, lending loans to ‘risky’ applicants is the largest source of financial loss (called credit loss). Credit loss is the amount of money lost by the lender when the borrower refuses to pay or runs away with the money owed. In other words, borrowers who default cause the largest amount of loss to the lenders. In this case, the customers labelled as 'charged-off' are the 'defaulters'. 

 

If one is able to identify these risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicants using EDA is the aim of this case study.

 

In other words, the company wants to understand the driving factors (or driver variables) behind loan default, i.e. the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.


## Conclusions
- Maximum loans are from pupose debt consolidation followed by credit card
- LC Grading system is working well, loans are graded in a way that there are less chances of Charged off with High Grade loans
- There are more chances of defaulters with higher interest rate
- Loans from small business have higher chances of Charged Off.
- public derogatory record and public banckruptcieshistory have higher chances of charged off loans
- percentage of charged off loans increases by Debt to Income ratio
- States California, New York, Florida and Texas contains maximum loans
- Number of loans increases as the month goes towards year end.
- There is positive co-relation between loan amount and Charged Off loans
- 

## Technologies Used
- numpy- version 1.24.3
- pandas- version 1.5.3
- matplotlib- version 3.7.1
- seaborn- version 0.12.2



## Contact
Created by @pujak19a - feel free to contact me!